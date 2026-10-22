代发 wailian999

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gtwssjnqcy.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtuujsdaul.html

[U80] PHP：代码规范修复
来源：http://dali.shzxlz.cn/Article/details/gtjxvuzvus.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gtuiqqgbsw.html

[U81] JS：初始化项目
来源：http://dali.yueranfly.top/Article/details/gtdwaakfrq.html

npm init -y;  npm i express
来源：http://dali.jyoumei.cn/Article/details/gthokpwqjc.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gttevrrxxp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gtkuspdexm.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gtybdfgoyr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gtbcaadboa.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxuanxn.top/Article/details/gtjzjubddn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnqzz.top/Article/details/gtmmjgtyee.html

[U85] JS：可选链
来源：http://dali.gaohongyu789.top/Article/details/gtufuuuhat.html

a?.b?.c
来源：http://dali.fengsongda.top/Article/details/gtuqbmbaki.html

[U86] JS：空值合并
来源：http://dali.jinqigufen.top/Article/details/gtuhoxgidh.html

a ?? b
来源：http://dali.jinghuilouyu.cn/Article/details/gtepzbxeos.html

[U87] JS：解构默认值
来源：http://dali.yonumen.top/Article/details/gtqqsnrrcg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.andypj.xyz/Article/details/gtdmunysjb.html

[U88] JS：对象展开合并
来源：http://dali.chenlongwang.top/Article/details/gttrwuqhim.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gtwkhmjwxu.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtasuzwphn.html

[...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtjoqlwutl.html

[U90] JS：数字数组排序
来源：http://dali.tianlin.xyz/Article/details/gtqmowfbuc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtrmbcedym.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtasxhdaio.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgufenzy.top/Article/details/gtgosutdhx.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gtvqwxawtc.html

structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtavigurio.html

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gtaqshwpsa.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gthsgrhqgi.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtwbpzlfsa.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gthvvcrxud.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsklgxjpd.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gtxswkkwnq.html

[U96] JS：async/await 与异常
来源：http://dali.jqgfzy.top/Article/details/gtuarhcovz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtpfbsskzr.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gtqvgmehtq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtnyhtgzph.html

[U98] JS：fetch 带 JSON
来源：http://dali.zycfv.cn/Article/details/gtzlfakkbk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjkyizcv.html

[U99] JS：事件监听
来源：http://dali.hfpthk.cn/Article/details/gtqxjqtssv.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gtznojedod.html

[U100] JS：DOM 查询
来源：http://dali.haohaochexian.top/Article/details/gtaczwdwzj.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gtgzbegcza.html

[U101] JS：classList 操作
来源：http://dali.gaohongyu789.top/Article/details/gtanfwhclm.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gtryilkahv.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gtqxzzvqeu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gtjobodepr.html

[U103] JS：定时器
来源：http://dali.vqdsnc.cn/Article/details/gtwbmzinun.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtotliwmvr.html

[U104] JS：防抖
来源：http://dali.pycfn.com/Article/details/gtzbqgcsaf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtigumyvdv.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gtjtgyyhqr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gtyptdilwa.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtqlwinmwt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbsufexv.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtdpwkozrn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtldptadud.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gtmffagddr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtfyppadof.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gtbacbolyi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtqdchnmvo.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gtqhcyldrn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jyoumei.cn/Article/details/gtaqpdzqtl.html

[U111] JS：对象转 Map
来源：http://dali.zycfv.cn/Article/details/gtvtzlyaxe.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gtwnzgjlpl.html

[U112] JS：字符串补位
来源：http://dali.jlsjyb.cn/Article/details/gtswevapfc.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtofcfsrnq.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gtqofghvro.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtyhibjbui.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gtyrqrlfrh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtoryfzqqj.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtmylgdbum.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtvvwnzcix.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jiagoushi.top/Article/details/gtqldeogbs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gtzemzfgsk.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gttdchrhtd.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gtjksvelqn.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gtvwkrkztz.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gtdgejtyek.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gtogorbcyi.html

npx vite build
来源：http://dali.yj202588.top/Article/details/gttedkaodr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jiagoushi.top/Article/details/gtfginskwt.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtnzuwzbak.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxpnzfpvn.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtdcewoewo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtukhullvi.html

按语言统计（条）：
来源：http://dali.jiagoushi.top/Article/details/gtdtaasvbn.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtusypnxwh.html

PHP ............ 252
来源：http://dali.hammf.cn/Article/details/gtulotklcq.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtbltjmhhx.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gtxgkfgmzu.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gteiviwtie.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gtkvvyefcb.html

Ruby ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtwgoyujyo.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gteplxzfvq.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gtpdnxzxrg.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtmfedvhvn.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gtlezxkyzo.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gtsrmeormp.html

Kotlin ......... 15
来源：http://dali.hywenlv.cn/Article/details/gtzmwglqqf.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gttdtpveqm.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gtszcuyqet.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtpwkwbctz.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gtxhrdmqhv.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtrgkuyahi.html

合计 ........... 2106 条
来源：http://dali.havefunace.top/Article/details/gtamixjypy.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gttzmzrtvj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtfmjwhntw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtipbmbfon.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtpkkaaxqb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtsvfmlest.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sysykeji.top/Article/details/gtansaeuwu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gtvcnlxgzn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtkwhqsnam.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtxzmhnkux.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtndwmface.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtsctiwfdv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtoudqmusi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtwsstnnlk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gthqkbirkq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtystolhlq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtsdlhbqoz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtrajdozyg.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gtzvvdogiq.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gtznvntqdf.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtybynnnix.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gtrxokiqgp.html

U 高频实用片段                         120
来源：http://dali.yanxiufei.cn/Article/details/gtnhxfduvz.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtgxmaivur.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxykplez.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtjcshqyqq.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gtrmhabgar.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtgrsefouo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sysykeji.top/Article/details/gtfzahhzef.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiisrnrp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtcdytyyyk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtscntqizq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daxiang520.top/Article/details/gtpkuvwrga.html

—— 文件结束 ——
来源：http://dali.shuidangran.top/Article/details/gtrbihrpmi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrhwtlvpc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gtudboofmq.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gtlfiwntce.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqokejzao.html

【收录内容】
来源：http://dali.hywenlv.cn/Article/details/gtrgrbtkba.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gtsbbtmuvw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yonumen.top/Article/details/gttpnwdwbv.html

SQL · Bash · C · C++
来源：http://dali.xylfe.cn/Article/details/gttdpzoayr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcstczcx.html

【使用说明】
来源：http://dali.hywenlv.cn/Article/details/gtejaovoyj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.birdmap.top/Article/details/gtdfydbkta.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtdntbnwie.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtcfpdhmif.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gtskunjyeb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.meibo888.top/Article/details/gtkdrubqxy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xinyue.icu/Article/details/gtuqpvuawe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gtodfwggan.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258888.top/Article/details/gtokovbltn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.redwolf501.top/Article/details/gtfuufkzes.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.havefunace.top/Article/details/gtnisygfdd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gtsgtkbfic.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yongpay.top/Article/details/gtmjcioird.html

【文件统计】
来源：http://dali.vqdsnc.cn/Article/details/gtacrakxmt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhongyouzk.top/Article/details/gtvsvejpcu.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtnuyqxnnr.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gtszfpctxq.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtbcfivcyf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtafpnlkls.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtolrhsohm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtjizyyghz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtnonfsyqv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yanxiufei.cn/Article/details/gtaotkcnaa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtketpuwtm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtwnoqmydh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtdesuebrs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtnzfjwmtn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gttziprxmb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtfdhnxooe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtzmeaqkuw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtozqkwgup.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtapaihczu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dashuyun.cn/Article/details/gtllxpvrrs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtfeyglqya.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sysykeji.top/Article/details/gtcalcnazf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtjtjpepbb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhengqikj.top/Article/details/gttwovcjef.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gtbnjmeyzw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtbjgmfqpv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgnhexmm.html

A. 基础语法与类型
来源：http://dali.pengpengdd.cyou/Article/details/gtiohhochr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttbmhegzl.html

[A01] Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtuucknnau.html

Py:   print("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gthqzlpjzo.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgufenzy.top/Article/details/gtzinaageo.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtwdioszsb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozsoptyy.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaicwxsc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtvaipzwtr.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gtdahephiq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtpxflmnox.html

[A02] 变量声明与赋值
来源：http://dali.mhx1999.top/Article/details/gtpehvwqbp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.svipenyu.cn/Article/details/gtalanupud.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtpcniwxuo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtxnlxisoa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtfjwdvsdv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gtkuizbbfz.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtsfunpudx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shangyingyoupin.top/Article/details/gtwnptzpny.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtbgktmvus.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtzhwjfyld.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gtgjkrckzh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtvhaeiurq.html

JS:   const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtebnzluvl.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjuzzxpn.html

Java: static final double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtgjgoedsq.html

Go:   const PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtwkpfitwu.html

Ruby: PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gtfgjdpgab.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtfbtulzoa.html

[A04] 判断变量类型
来源：http://dali.hnqzz.top/Article/details/gteslscxlj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxinkj.top/Article/details/gtywpgqjjj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gtdcmjftci.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gtlcoqqidy.html

TS:   typeof x; x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gthweqmlxm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.c1oappe.top/Article/details/gtuowobaai.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.bjfxy.top/Article/details/gtusvbmgin.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gogol.net.cn/Article/details/gtlxaisucy.html

C#:   x.GetType().Name; x is int
来源：http://dali.hywenlv.cn/Article/details/gtjquwvlbp.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gthifnvser.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pycfn.com/Article/details/gtihelhclz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtsekweeow.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtfrfshsft.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtrpyawkli.html

Java: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtppxcoksd.html

Go:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gttbwehovb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gthiraexyc.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtawambydm.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvuwyhwp.html

Py:   int("42"); float("3.14")
来源：http://dali.daria6918.cn/Article/details/gtsyfwmnsk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tianlin.xyz/Article/details/gthbvvkdxj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.316326.xyz/Article/details/gthevuqsew.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtbhgdoblx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gtpailstqh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gtcosdjdgq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gtoawucnbd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.havefunace.top/Article/details/gtqndiiidp.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmwwyzm.html

Py:   str(42)
来源：http://dali.yonumen.top/Article/details/gtfbtenpzn.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangdashe.top/Article/details/gtycrqocfp.html

JS:   String(42); (42).toString()
来源：http://dali.chenlongwang.top/Article/details/gtrjuvecfq.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gtnozvqqyz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aibaodan.cn/Article/details/gtwwebyrna.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtekgtalke.html

Ruby: 42.to_s
来源：http://dali.chenzaomai.com/Article/details/gtakduhblv.html

C#:   42.ToString()
来源：http://dali.chenlongwang.top/Article/details/gtpgjelbdb.html

[A08] 取整与四舍五入
来源：http://dali.havefunace.top/Article/details/gtrumghhkr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gtzvqzobpc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hysaishi.cn/Article/details/gtamtzdhxw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtkbdtgslt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yongpay.top/Article/details/gtrorjjpmr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtdevfuxud.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtuqjeejjy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sufxvd.cn/Article/details/gtphqfxivg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtruyvbxqe.html

[A09] 绝对值与最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuhfytwp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtgrnqseos.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtpyzyevgl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtnmlxzeik.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtusimdpoq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtrjkqztuh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangdashe.top/Article/details/gtxujebuvj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangdashe.top/Article/details/gtpwrvrzce.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtqttpveho.html

[A10] 生成随机数
来源：http://dali.svipenyu.cn/Article/details/gtynopacos.html

Py:   import random; random.randint(1, 100)
来源：http://dali.kuanghao11.cn/Article/details/gtpvxoksaq.html

PHP:  random_int(1, 100);
来源：http://dali.yueranfly.top/Article/details/gttpdtkcyp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtnjklnpyp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gtkjxhufhv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuanzx.com/Article/details/gtmjtfncbp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hnxiangtu.top/Article/details/gtdgougvvi.html

Ruby: rand(1..100)
来源：http://dali.bjfxy.top/Article/details/gtbszpkztb.html

C#:   new Random().Next(1, 101)
来源：http://dali.9152youxi.cn/Article/details/gtrkqefjaq.html

[A11] 条件表达式（三元）
来源：http://dali.zhengqikj.top/Article/details/gtyaurcnuu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yanxiufei.cn/Article/details/gtsfobebnk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gthikolccc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtzshotqfp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtjvjsgihv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtimbxnlqr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tanke756.top/Article/details/gthjcomdwx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtprrehujj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtifccxygd.html

[A12] 字符串插值 / 格式化
来源：http://dali.c1oappe.top/Article/details/gtnovaoinj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenjidiqi.icu/Article/details/gtxicgmdzu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhiwuduotai.top/Article/details/gtpntslazv.html

JS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gtscgvzuzj.html

TS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gtzvlzzzgp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.quarkkingdee.top/Article/details/gtlpywxoxt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.0kj1m.cn/Article/details/gtazuonpvx.html

Ruby: "Hello, #{name}!"
来源：http://dali.316326.xyz/Article/details/gtfonrykda.html

C#:   $"Hello, {name}!"
来源：http://dali.cdnleiting.top/Article/details/gtnobvlqev.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yj202588.top/Article/details/gtkflkhyjw.html


<!-- 参考信息 -->