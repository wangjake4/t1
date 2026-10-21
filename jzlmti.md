代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.guowangkeji.top/Article/details/gtejkgncsk.html

composer require psr/container
来源：http://dali.gzhubu.top/Article/details/gtjcwkqakq.html

[U76] PHP：简单路由
来源：http://dali.fengsongda.top/Article/details/gtgixousoo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gtfgvvtayn.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gtuceovrlk.html

composer require twig/twig
来源：http://dali.snrcjt.cn/Article/details/gtraaacodq.html

[U78] PHP：单元测试
来源：http://dali.jianghu66.top/Article/details/gtanndbire.html

composer require --dev phpunit/phpunit
来源：http://dali.zycfv.cn/Article/details/gtomxsosic.html

[U79] PHP：静态分析
来源：http://dali.shangyingyoupin.top/Article/details/gthnibulmy.html

composer require --dev phpstan/phpstan
来源：http://dali.haohaochexian.top/Article/details/gtugyjubpn.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gtgkgdqrqw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hongshengwenyu.top/Article/details/gtvdoovwfx.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gtwsffuijl.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gtkrycabuf.html

[U82] JS：package.json 脚本
来源：http://dali.jyoumei.cn/Article/details/gtrxoiesum.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gtkoscfqhg.html

[U83] JS：ES Module 导入导出
来源：http://dali.316326.xyz/Article/details/gtpnuchegi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtlputunks.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gtdqnulyeb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cashguo.top/Article/details/gtehvyfgsw.html

[U85] JS：可选链
来源：http://dali.tanke756.top/Article/details/gtsgtvlexm.html

a?.b?.c
来源：http://dali.chenzaomai.com/Article/details/gtwgkpvkin.html

[U86] JS：空值合并
来源：http://dali.wangshuangyany.cn/Article/details/gtcfebebxk.html

a ?? b
来源：http://dali.chenjidiqi.icu/Article/details/gtlxhusxbg.html

[U87] JS：解构默认值
来源：http://dali.sufxvd.cn/Article/details/gtrsmdgcos.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gtqoedbaiu.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gtrrsvuuzj.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gtplrwjbjd.html

[U89] JS：数组去重
来源：http://dali.ehwqpu.com/Article/details/gtkgbizavz.html

[...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtekzmzxzq.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gtnkqwsjlq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtcnmiywbl.html

[U91] JS：对象键值遍历
来源：http://dali.kuanghao11.cn/Article/details/gtmsvioevb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gtosseepab.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gtvlxxwppz.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtgcqbpxex.html

[U93] JS：模板字符串
来源：http://dali.jinqigfzy.top/Article/details/gtpzkgwfto.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gtznlutikc.html

[U94] JS：箭头函数
来源：http://dali.sysykeji.top/Article/details/gtbhnbylbx.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtijtlxsqe.html

[U95] JS：Promise 包装
来源：http://dali.zhongyouzk.top/Article/details/gtubxlwvir.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gtcunqkjck.html

[U96] JS：async/await 与异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtbefjjpwv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtljbkfgjb.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gtxzuohogv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtbxtrtzoc.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtfiilejbf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangdashe.top/Article/details/gtcorxoilb.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gtotvzcfce.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gthhmxvtni.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtlhphlbgy.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gtmumdwztk.html

[U101] JS：classList 操作
来源：http://dali.ybcxt.top/Article/details/gtwnhtduoe.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtsjvtotcm.html

[U102] JS：本地存储
来源：http://dali.shzxlz.cn/Article/details/gtbpixvkiq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ydzc1.top/Article/details/gtjvhudxjt.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gtqzlbqaix.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gtohjievur.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gttmyowiub.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtlqqmhcpk.html

[U105] JS：节流
来源：http://dali.nanxinkj.top/Article/details/gtpwpubvam.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gthrpdecio.html

[U106] JS：日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtbpdgxkhj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtgaxjpilg.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtzwzdsdof.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtammkjiaq.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gtphymvxkq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtxnpamwiu.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gtcgaqhsak.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtsxvlaoxe.html

[U110] JS：数组分块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqxxsixl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gtrurphqpg.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gtykdynedl.html

new Map(Object.entries(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqestejb.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtfkolwwns.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtqfsuzqwu.html

[U113] JS：正则替换全部
来源：http://dali.yj20258888.top/Article/details/gtbmwebvlx.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtiommrwpz.html

[U114] JS：JSON 深比较
来源：http://dali.gogol.net.cn/Article/details/gtvfsfbwsj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gttsqduzfp.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gttxyqlkcr.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtpzntprhr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.c1oappe.top/Article/details/gtegmewnzt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gthtbrhnly.html

[U117] JS：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtrwkylcxs.html

npm i -D vitest;  npx vitest
来源：http://dali.yvedp.cn/Article/details/gtcryguhxf.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gtlcodhnvh.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtzrkltofk.html

[U119] JS：生产构建
来源：http://dali.wangdashe.top/Article/details/gtjdpyhmqv.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gtfiubkdeq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtgtdteeem.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtuivmnoaj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtaildyggf.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gtxvxsvcug.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjncvdcvr.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gtdtxpyrlt.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gthnsyayxr.html

PHP ............ 252
来源：http://dali.tanke756.top/Article/details/gttgjdxabt.html

JavaScript ..... 252
来源：http://dali.0kj1m.cn/Article/details/gtqytcjrwq.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtyyoddfaf.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtjhanamzo.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gtsxzyjnle.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtlzdamivs.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gtklzqobtp.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gtztfafshq.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtdkgsynmz.html

SQL ............ 90
来源：http://dali.tianlin.xyz/Article/details/gttwygtisb.html

Bash ........... 80
来源：http://dali.jlsjyb.cn/Article/details/gtfiteajfq.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtrrwkqlun.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtidlkzgyt.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtpdplchay.html

Perl ........... 10
来源：http://dali.zhoulong.xyz/Article/details/gtsynyyqwb.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtmlwxyach.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtozweelxy.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtjwmqdfdy.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtmwsatxns.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtmygjpvly.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtygbfcwdv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqfdfnpa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtfdiqczdi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hammf.cn/Article/details/gtbixmidwd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtrhdeqpvy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gthipdxeqh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtdaobhkjm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtsdktfbva.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gturilsdry.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscebhtxw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtllyvdhhe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtaotpvrlo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gtfeykbfxq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtwuyqkavd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtmjdymblt.html

Q SQL 专题                              90
来源：http://dali.jianghu66.top/Article/details/gtxlvyqdro.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gtskvaphoq.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gtmioomagd.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtvocpmifm.html

U 高频实用片段                         120
来源：http://dali.iojbl.cn/Article/details/gtgclyeuvi.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtapvqnukp.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtefetuxyu.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqjqqrem.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtzkvzzyoo.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtltpblqsd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtfexzblui.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ehwqpu.com/Article/details/gtaxcpvgbh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yongpay.top/Article/details/gtparbqtqu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gthtsxckzs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258888.top/Article/details/gtwvonyzjv.html

—— 文件结束 ——
来源：http://dali.ppjwa.cn/Article/details/gtcflaxpoa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdeykldpc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenzaomai.com/Article/details/gtrtnnilva.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gthdtwhzcc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpzdcjxqr.html

【收录内容】
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnggizan.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.birdmap.top/Article/details/gttplxwxuo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtyjmnqcsx.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhqimyjd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigfzy.top/Article/details/gtwqntgvzw.html

【使用说明】
来源：http://dali.tianlin.xyz/Article/details/gtahjrhrwd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gtcoayvnut.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hysaishi.cn/Article/details/gtahifbgts.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gtsstmwffj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gtyinwexan.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangdashe.top/Article/details/gtdpeozcym.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gtiqwvxhwr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zdqjudy.top/Article/details/gtatooduih.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gaohongyu789.top/Article/details/gtzhrnlbij.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cdnleiting.top/Article/details/gtrvardvbj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xylfe.cn/Article/details/gthzqejpsx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sweek.top/Article/details/gtypfcriyb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ydzc1.top/Article/details/gtwtapvkml.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gthvgjdbro.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnwvhofd.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtmjidejyo.html

目  录
来源：http://dali.xylfe.cn/Article/details/gtkbcvgvrd.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtvoqvzqcn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtpwphzhdl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtkoumffuc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxazdudqh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gtwlzwtezs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gtjgpwppcl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtcyfxvbht.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtxaflkuqw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtzevdwthc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtspejfkas.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtwcgmpwqz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtnqstjmdo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtabbfjcgo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtmenkixll.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jiagoushi.top/Article/details/gtftznajvc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj202588.top/Article/details/gtfgnrowqx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtlyyssbjr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.kuanghao11.cn/Article/details/gtaysnxkvb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.316326.xyz/Article/details/gthlhmapll.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.andypj.xyz/Article/details/gteukuvqmp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtuxtlalyd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtiqmzlnji.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttqlumykv.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoszvswba.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxxkbybku.html

[A01] Hello World
来源：http://dali.chenzaomai.com/Article/details/gtwxstyftq.html

Py:   print("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkkvjykx.html

PHP:  echo "Hello, World!";
来源：http://dali.gaohongyu789.top/Article/details/gtufjzvzbd.html

JS:   console.log("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gteujawkin.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gtvhrhtcms.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtxcjjcgld.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gtfcfdryih.html

Ruby: puts "Hello, World!"
来源：http://dali.feifeiyinyue.top/Article/details/gtqcgzketn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gttsmluvja.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gteykfmlhe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.316326.xyz/Article/details/gtyaeucvwi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtxjukllqs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnasnemyw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgfzy.top/Article/details/gthbsqwxky.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiofejne.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gtumxdlzza.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xziqi.cn/Article/details/gtxxmurvmq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtmmspuoiu.html

[A03] 常量定义
来源：http://dali.birdmap.top/Article/details/gtkrroknav.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shangyingyoupin.top/Article/details/gtcjnsyfqa.html

PHP:  const PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtjnuyqkap.html

JS:   const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtalquqtxz.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtmajwyyjc.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtecakqdlu.html

Go:   const PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiqosjlj.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gtyvtdltla.html

C#:   const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtqvzqgyno.html

[A04] 判断变量类型
来源：http://dali.sweek.top/Article/details/gtwrnxvzzt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gtxvhzebaf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtasdrmewy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuanzx.com/Article/details/gtlnanmesv.html

TS:   typeof x; x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtxcxniwrv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gtxommgguo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxinkj.top/Article/details/gtfbnavsip.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gtsnuejush.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgerxrzwp.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gtamuuhysm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fengsongda.top/Article/details/gtuugsafry.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtjqwbfkgi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtxxuyiswh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtqghwyyvn.html

Java: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtqvbbysbs.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtjxpxfvus.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtmnxoijrd.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtvwamqnmh.html

[A06] 字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtayrhpfjp.html

Py:   int("42"); float("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtgelxbxgw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenlongwang.top/Article/details/gtpvsbrxjy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtcilcsklu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtwqpatcee.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj202588.top/Article/details/gtezxcvchx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.kuanghao11.cn/Article/details/gtsinmncis.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenzaomai.com/Article/details/gtoxsqamwb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gtjjcfdaav.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacbfvcdg.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gttjcpdrjj.html

PHP:  (string) 42; strval(42)
来源：http://dali.tanke756.top/Article/details/gttfhtugac.html

JS:   String(42); (42).toString()
来源：http://dali.xziqi.cn/Article/details/gtsfstzezf.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gttyojgagb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.redwolf501.top/Article/details/gtpilfeqwh.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gtcmapzkdd.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gtpfrqkbku.html

C#:   42.ToString()
来源：http://dali.tianlin.xyz/Article/details/gtnkrgfuos.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gtojpzbnvh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtpdtdudbo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenjidiqi.icu/Article/details/gtestackjb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtfhhmhsgp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.meibo888.top/Article/details/gtsvdjkncm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtfmpuutot.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gthdedzqje.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenjidiqi.icu/Article/details/gtpzdjcdps.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtzflzbbze.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtieaqboln.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtjecggank.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtfqdjofxe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtxhfkvzbm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtbtoihdgo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqeklron.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fzhhl.top/Article/details/gtxtadjjgg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gtzwucbtey.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtajekazmz.html

[A10] 生成随机数
来源：http://dali.yongpay.top/Article/details/gtxklqzlew.html

Py:   import random; random.randint(1, 100)
来源：http://dali.9152youxi.cn/Article/details/gtyrqiqwyw.html

PHP:  random_int(1, 100);
来源：http://dali.nanxinkj.top/Article/details/gtpbxazoqg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtszmvipee.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gtkveqgqgh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtsytheivd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hfpthk.cn/Article/details/gthkqtohgg.html

Ruby: rand(1..100)
来源：http://dali.hongshengwenyu.top/Article/details/gtyxynjvia.html

C#:   new Random().Next(1, 101)
来源：http://dali.pengpengdd.cyou/Article/details/gtctjunltq.html

[A11] 条件表达式（三元）
来源：http://dali.shuidangran.top/Article/details/gtqhvwfgvk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ivvv.top/Article/details/gtyouhsdxk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtlktpxppt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtihesplxf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtypsgxtxl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtiaibqyeh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fzhhl.top/Article/details/gtoyxovxgc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtozdxlizs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtmmlbjzne.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhixingplan.top/Article/details/gtsdumhpll.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guowangkeji.top/Article/details/gtthguhgme.html


<!-- 参考信息 -->