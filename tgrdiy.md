代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtietarsab.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gtywcodslq.html

[U76] PHP：简单路由
来源：http://dali.ybcxt.top/Article/details/gttmspclem.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.bjfxy.top/Article/details/gtkuwpxqdv.html

[U77] PHP：模板渲染
来源：http://dali.yj20258.top/Article/details/gtnekagtdk.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gtiwmvquxw.html

[U78] PHP：单元测试
来源：http://dali.gzhubu.top/Article/details/gtokcnrgtj.html

composer require --dev phpunit/phpunit
来源：http://dali.daria6918.cn/Article/details/gtnlkxxfyr.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtblohqjjv.html

composer require --dev phpstan/phpstan
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkghzuob.html

[U80] PHP：代码规范修复
来源：http://dali.pycfn.com/Article/details/gtsaasiyln.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guowangkeji.top/Article/details/gtenuhezvp.html

[U81] JS：初始化项目
来源：http://dali.aibaodan.cn/Article/details/gtyinvcjjq.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gtiyxudonu.html

[U82] JS：package.json 脚本
来源：http://dali.tian-w.cn/Article/details/gttauiwdng.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gtugaiaudc.html

[U83] JS：ES Module 导入导出
来源：http://dali.aizwys.cn/Article/details/gtkselwaiw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtxqkccskn.html

[U84] JS：CommonJS 写法
来源：http://dali.sufxvd.cn/Article/details/gtlewklucb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gthtfkjoim.html

[U85] JS：可选链
来源：http://dali.shuidangran.top/Article/details/gtwkewuczi.html

a?.b?.c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogsdlgti.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gtfqvwpsuy.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtpokljcvb.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gtzmoirxcb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gtrobjrgpv.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gtfvlkkstm.html

{ ...a, ...b }
来源：http://dali.xuetiantiany.cn/Article/details/gtvprrwhmh.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gtozapjcal.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcstcjyv.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtyvseovao.html

[...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtdpkgmegm.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gtdutdueyz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.mhx1999.top/Article/details/gtvgccnsfp.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvncuecy.html

structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtmnglbakf.html

[U93] JS：模板字符串
来源：http://dali.sufxvd.cn/Article/details/gtpievpsfl.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gtnlrmomjm.html

[U94] JS：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtnviyqprb.html

const double = x => x * 2;
来源：http://dali.cashguo.top/Article/details/gtzftvpnwn.html

[U95] JS：Promise 包装
来源：http://dali.nanxuanxn.top/Article/details/gtovquoguu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gtwyvapnzc.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gtjivwwsfx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtxwzgcdam.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gtlvexwnfl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtabtsedfp.html

[U98] JS：fetch 带 JSON
来源：http://dali.nwbrower.top/Article/details/gtsogxvuge.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gtkfluwkxj.html

[U99] JS：事件监听
来源：http://dali.ehwqpu.com/Article/details/gtavtotkia.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gtnzdzgwfe.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtljpkbxwe.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gtvswkwsiu.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gtctpwlxaf.html

el.classList.toggle("active")
来源：http://dali.havefunace.top/Article/details/gtrmsawhpm.html

[U102] JS：本地存储
来源：http://dali.ybcxt.top/Article/details/gtgazqzcde.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jlsjyb.cn/Article/details/gtarbssvzw.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gtiiezylxu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gtwidmszsy.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtqifoblwq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtaofqtjrp.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gtublqzlwt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gtqurrxzgq.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtnxjqxwhi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenjidiqi.icu/Article/details/gtfmcwkxno.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtntyypcun.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtxsrzhgse.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gthtzxuekg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gtjvmkhsxl.html

[U109] JS：数组分组
来源：http://dali.zdqjudy.top/Article/details/gteuccmlka.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtdwfjjpbf.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gtmjhttvvy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gtxvxpmust.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtjligbytg.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gtdxzyodci.html

[U112] JS：字符串补位
来源：http://dali.bjfxy.top/Article/details/gtnvgfoahn.html

"7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtnkurrpvv.html

[U113] JS：正则替换全部
来源：http://dali.sxryk.cn/Article/details/gtxvyhbaen.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtoqnqoeoo.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gthvpkracz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtffamuy.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgrxmnso.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtozcpyvad.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dianchejie.cn/Article/details/gtvzhzfnxz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjannktjn.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtmvutipns.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gtqyyjypan.html

[U118] JS：开发服务器
来源：http://dali.fzhhl.top/Article/details/gtdubirgbk.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gtxjvuievp.html

[U119] JS：生产构建
来源：http://dali.xuanzx.com/Article/details/gthlrhxidk.html

npx vite build
来源：http://dali.sxryk.cn/Article/details/gtqbhqrxcj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shangyingyoupin.top/Article/details/gtfihgwkzr.html

import.meta.env.VITE_API_URL
来源：http://dali.hnxiangtu.top/Article/details/gtrcxwqgxv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgiisodpm.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gtblqjbgza.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywdguhzd.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtvfidbvyv.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtuovmcufy.html

PHP ............ 252
来源：http://dali.zdqjudy.top/Article/details/gtkbskyeaz.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gtinzcwgvu.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gtiquwsccu.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gtglewgfkk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtkyodcotc.html

Ruby ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtonvhbdov.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtanmxanso.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gtxitaqdng.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzvruraw.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gtebhtdudz.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoipguej.html

Kotlin ......... 15
来源：http://dali.haohaochexian.top/Article/details/gtmmupycco.html

Swift .......... 15
来源：http://dali.yonumen.top/Article/details/gtzykarosv.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gtzhlgvqpg.html

Perl ........... 10
来源：http://dali.snrcjt.cn/Article/details/gtpmtvoblj.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gthpfvcqtm.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtaievczmk.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gtbeyqgcqd.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gtdzzvtybv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzauweyg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtejhywcya.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtoqdxohhg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtdahicgdd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtfqnzkypm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtfdeqylmq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtjmpmaule.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtdpzaydob.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtptlfryil.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gtvvyixdif.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gttupryjfi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtyibtaybt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtvhkpkozv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtirgxfplx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gtnpqeynjh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuzqfwjw.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gtjuxtlpug.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtjwyoujqf.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gtnnwjhcqb.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gtxjdvxhxv.html

U 高频实用片段                         120
来源：http://dali.zycfv.cn/Article/details/gtateqdabh.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtybnnpwui.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtivwxrdib.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtwbtmepqx.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtukfzzcml.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtuciehwri.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtasrlhfjy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yongpay.top/Article/details/gtgxhtadhg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hammf.cn/Article/details/gtrkumwwgk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gtcuiujwlp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cheryme.top/Article/details/gtsdaihgvj.html

—— 文件结束 ——
来源：http://dali.xinyue.icu/Article/details/gtmboyvshj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtukczgcbn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtbnrbmaqn.html

Common Programming Examples Cheat Book
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugihmvhq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtifxizzbj.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gtqcjasqfp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuetiantiany.cn/Article/details/gtptpkpkqn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gttxlzbizp.html

SQL · Bash · C · C++
来源：http://dali.dashuyun.cn/Article/details/gthsxgxeub.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuetiantiany.cn/Article/details/gtzwnvzzxz.html

【使用说明】
来源：http://dali.chenjidiqi.icu/Article/details/gtlbjaivnl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gtxexkaazm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.andypj.xyz/Article/details/gtpsuzesgq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gttijpcedg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gttaijgbdz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.meibo888.top/Article/details/gtlvwuztrl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cheryme.top/Article/details/gttgguzxwm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.feifeiyinyue.top/Article/details/gtjkzhrwzb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sxryk.cn/Article/details/gtqeulhwhg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yueranfly.top/Article/details/gteelusbaz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtbsqqgans.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gtulytqrlj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhengqikj.top/Article/details/gthcqsdczv.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gtebiswazj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.quarkkingdee.top/Article/details/gtrjkcnhrk.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtfmgmevyo.html

目  录
来源：http://dali.hammf.cn/Article/details/gtedjsseyy.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtnmlxyqbi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtayghwxjk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtiylfczin.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gthuilmpcf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvoitsnx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dashuyun.cn/Article/details/gtgquiuaum.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtnfnloheu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtpjupfyeo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtcvwprcxz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gteookokis.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtjmoycjew.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtqlseyrao.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtsuczwftj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtzpuaunoq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtjhnjirsx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zdqjudy.top/Article/details/gtmdkhtwct.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtqejcahss.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbbxbbie.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tian-w.cn/Article/details/gtfecrcvre.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuxming.cn/Article/details/gtaynmnndc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtuwefojjy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtabotkxrz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtajqiackl.html

A. 基础语法与类型
来源：http://dali.sufxvd.cn/Article/details/gtrqmdysjd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthasqlmja.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gtidhdheuv.html

Py:   print("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gtjtroupyt.html

PHP:  echo "Hello, World!";
来源：http://dali.gotoacloud.top/Article/details/gtagsmyrrh.html

JS:   console.log("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtmndbzyhs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxinkj.top/Article/details/gtqvtafvsr.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtzzshahon.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gtokmaobia.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gtrwfcjtut.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtpqpurigt.html

[A02] 变量声明与赋值
来源：http://dali.yvedp.cn/Article/details/gthtqgfdls.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yongpay.top/Article/details/gtaopafhlt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfywzqgj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258.top/Article/details/gtqvpfjity.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.birdmap.top/Article/details/gtknwkmoxr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtdnbjyhnb.html

Go:   name := "Alex"; age := 20
来源：http://dali.gogol.net.cn/Article/details/gttqsccllr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.birdmap.top/Article/details/gtckqxmeip.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtkgfgvynv.html

[A03] 常量定义
来源：http://dali.mhx1999.top/Article/details/gtfgeqecdz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gaohongyu789.top/Article/details/gtivdmwthy.html

PHP:  const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkrecjhl.html

JS:   const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtitmwnbqn.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gteqebvqgu.html

Java: static final double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtvflkdddg.html

Go:   const PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gtxbzdzfvk.html

Ruby: PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gtjdfjhkof.html

C#:   const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtygfimjnj.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gttwemlbhi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnxiangtu.top/Article/details/gtbcmjqutm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.0kj1m.cn/Article/details/gtmctlvltf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gtwtegwggp.html

TS:   typeof x; x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtducdotzl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjcukrar.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenjidiqi.icu/Article/details/gttvxfpxlv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jianghu66.top/Article/details/gtgxeqbxlf.html

C#:   x.GetType().Name; x is int
来源：http://dali.havefunace.top/Article/details/gtrehxyxwe.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gtbubnprtn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gtpdawbfoh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gtgzkwxlcp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtrphgtedj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtxynasnuf.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtmtclomjb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtrpwcutno.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gttvhqvsvj.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtxtdenbjr.html

[A06] 字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtuvmthafz.html

Py:   int("42"); float("3.14")
来源：http://dali.yonumen.top/Article/details/gteeviiohh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gtwqdunoxf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtihcygpov.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtvlbdenwl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtvxpxhsqi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xinyue.icu/Article/details/gttdpualhj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenzaomai.com/Article/details/gtxphrxcqo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shuidangran.top/Article/details/gtpiahlufs.html

[A07] 数字转字符串
来源：http://dali.gaohongyu789.top/Article/details/gthkybtilr.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gtuabdfxne.html

PHP:  (string) 42; strval(42)
来源：http://dali.pycfn.com/Article/details/gtrmektxso.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gtayjyfzcp.html

TS:   String(42)
来源：http://dali.hnxiangtu.top/Article/details/gtenhxyasa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnqzz.top/Article/details/gthcxpgdkr.html

Go:   strconv.Itoa(42)
来源：http://dali.havefunace.top/Article/details/gtbnaxdudd.html

Ruby: 42.to_s
来源：http://dali.chenzaomai.com/Article/details/gtzzxwjced.html

C#:   42.ToString()
来源：http://dali.sysykeji.top/Article/details/gtaeodhlrs.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gtlkkhsvun.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtbidyhyhd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.sysykeji.top/Article/details/gtgjgswbnd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtpmittafm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hysaishi.cn/Article/details/gtykfhoiaq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtzcnqmenc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtwuxedswg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gtdknjebru.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtcuodebag.html

[A09] 绝对值与最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtplchvoyo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtlsdlazie.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtacckxkzg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtvmhqjtpr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gtktzplyhz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtarbdjnke.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sufxvd.cn/Article/details/gttnzetwzd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtffdthtot.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtwcmebobf.html

[A10] 生成随机数
来源：http://dali.sufxvd.cn/Article/details/gtcuwnjbst.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhoulong.xyz/Article/details/gtcurgntqt.html

PHP:  random_int(1, 100);
来源：http://dali.smart0.xyz/Article/details/gtxxlqcrhv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtbnuvdcnb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gtdqkzxcmb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yonumen.top/Article/details/gtyqeoejaq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuxming.cn/Article/details/gtnxzxpppa.html

Ruby: rand(1..100)
来源：http://dali.kuanghao11.cn/Article/details/gtvepaetjs.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gtqutbskur.html

[A11] 条件表达式（三元）
来源：http://dali.sweek.top/Article/details/gtjjybgyon.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cucudq.cn/Article/details/gtreokplpt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gttxhrwrbf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtnmgymlbh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtsfxepogo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtgjlhrbvb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj202588.top/Article/details/gtblbfccgg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtracpjigh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtqlyjccbz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zycfv.cn/Article/details/gtncdszvap.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jqgfzy.top/Article/details/gtwkrpytxm.html


<!-- 参考信息 -->