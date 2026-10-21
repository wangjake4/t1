代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gtfqcqmhrj.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtdlameoaw.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtcvnvhbcj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gtgpttxfus.html

[U77] PHP：模板渲染
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijvyeeuh.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gtkoikbgko.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gticxwucqt.html

composer require --dev phpunit/phpunit
来源：http://dali.pengpengdd.cyou/Article/details/gtevdrdkah.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtehhkyhtx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhixingplan.top/Article/details/gtjtynatpf.html

[U80] PHP：代码规范修复
来源：http://dali.c1oappe.top/Article/details/gtucxobfpe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jlsjyb.cn/Article/details/gtutlglmdj.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gtzzxzalcn.html

npm init -y;  npm i express
来源：http://dali.nanxinkj.top/Article/details/gtdokhubvp.html

[U82] JS：package.json 脚本
来源：http://dali.gogol.net.cn/Article/details/gtiytkgpgt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gtmksgbgzq.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gtmwtqqxue.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtmurffltu.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gtbqqpkhwq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnqzz.top/Article/details/gtbilqtklj.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtbhbqrwnr.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gtqjsmoiro.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gtthkuskdo.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtiwnrsykr.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gtkqbjrgmq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ivvv.top/Article/details/gtcppncjjm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gtczyzqtao.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gtmytujard.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gtrgyymgbe.html

[...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtmddfeqeg.html

[U90] JS：数字数组排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhnhnmer.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gttoxgluhp.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigufen.top/Article/details/gthnsrejht.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gtlepatzkz.html

[U92] JS：深拷贝
来源：http://dali.c1oappe.top/Article/details/gtpxyqroer.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtlbtvfxew.html

[U93] JS：模板字符串
来源：http://dali.guannengcc.top/Article/details/gtazzgshlz.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gtscbhcgaq.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gtdvtazucv.html

const double = x => x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtclfxlaur.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gtxccqbkof.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtmnggctqe.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gtjsmcsdgh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtshfxoejc.html

[U97] JS：并发请求
来源：http://dali.pycfn.com/Article/details/gtlrlowahp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtdpepngzs.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gtgwsvvpik.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tian-w.cn/Article/details/gttchrgrbb.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gtfrhppyuh.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrdihqel.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gtxwnwntsw.html

document.querySelector(".item")
来源：http://dali.zycfv.cn/Article/details/gtlfyfoelj.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gttqmfqiqj.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gtwolytxpe.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gttppfnexb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pycfn.com/Article/details/gtaswduybs.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gtpkihmylb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aibaodan.cn/Article/details/gthjacpjij.html

[U104] JS：防抖
来源：http://dali.jianghu66.top/Article/details/gtnjmvafhu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtpcdaocyl.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtbjtwrhgp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtqbhqlvsy.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gtnvkzgpul.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gtoudkraty.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtanmecixb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtoigmqjrf.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gtkhagthiv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gtaktwcqqw.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyitosce.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtowbzryfi.html

[U110] JS：数组分块
来源：http://dali.cashguo.top/Article/details/gtngvhgfze.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtjdvcsnro.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gtlwfpxdkk.html

new Map(Object.entries(obj))
来源：http://dali.shuidangran.top/Article/details/gtjbszttbp.html

[U112] JS：字符串补位
来源：http://dali.yj20258888.top/Article/details/gtdlyicnnq.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzsreflw.html

[U113] JS：正则替换全部
来源：http://dali.aibaodan.cn/Article/details/gtoyxlurkj.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtgdxuthnm.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gtnunceplz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtfcobafgq.html

[U115] JS：生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtbtjtcyev.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtczqitcpg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gtztiyowaf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxjevmaco.html

[U117] JS：单元测试
来源：http://dali.nwbrower.top/Article/details/gtfpjntgse.html

npm i -D vitest;  npx vitest
来源：http://dali.gzhubu.top/Article/details/gtuxpnwsof.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gtpdummixc.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gtcvpiyndv.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gtigekqznw.html

npx vite build
来源：http://dali.sysykeji.top/Article/details/gtpdwjwezc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqerwlqfr.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtqypvviuj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtamnigfxj.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gttwbjzqgb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrikvvkaj.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtzrumpaai.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gtnojvhotc.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtumnetzkn.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtzsonmnjn.html

TypeScript ..... 212
来源：http://dali.svipenyu.cn/Article/details/gtejbsmeon.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gtcpolezik.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwsscegy.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtudbtsudt.html

C# ............. 212
来源：http://dali.fzhhl.top/Article/details/gtgykunpsf.html

C .............. 30
来源：http://dali.jyoumei.cn/Article/details/gtusmqhyam.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtcjmrysmv.html

SQL ............ 90
来源：http://dali.fengsongda.top/Article/details/gtbtnidvij.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gtsnovbxug.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtsjelozyr.html

Swift .......... 15
来源：http://dali.mhx1999.top/Article/details/gtwvojfasx.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gtzwsowqhb.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gtczffklcr.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gtjcttevst.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtppkwiycm.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshgpygmg.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gtrtziqksx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gtxrpcixky.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtkuwyhwua.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtuybyfwyp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtldulqvow.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gtlcdvwixp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gteodstrdx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gteybtpids.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtcdewlred.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtrltnvdmd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtsgxslxue.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtnaojchjc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtkumidetv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtybofdhqh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtlmsxzccj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gtmfxcolhq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtkvvpgdvy.html

Q SQL 专题                              90
来源：http://dali.jqgfzy.top/Article/details/gtnxrforkq.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gtnhlmlmat.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gtsstbzavr.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gtectwsaqd.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtldiooheo.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtzwjuwerd.html

合计                                  2106 条
来源：http://dali.yangfankeji.com/Article/details/gtpndlkqto.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gttwkfosrs.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gtfubliduk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtolqdfaol.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gthgrybylq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtpvleiopo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hongshengwenyu.top/Article/details/gtaeluskzg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gtgilsxhex.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yangfankeji.com/Article/details/gtobbrtkgh.html

—— 文件结束 ——
来源：http://dali.redwolf501.top/Article/details/gtholtjaux.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnaqibxbk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuanzx.com/Article/details/gtyoihjwqu.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gtchpdmwhc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtscmyaqtm.html

【收录内容】
来源：http://dali.wangshuangyany.cn/Article/details/gtzibrsuax.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.kuanghao11.cn/Article/details/gtsnxhmphj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cucudq.cn/Article/details/gtxrodtftd.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gttlbflzvy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.quarkkingdee.top/Article/details/gttxrugahm.html

【使用说明】
来源：http://dali.kuanghao11.cn/Article/details/gtltubldlc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gtxvwtnzrv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmjsgmne.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fzhhl.top/Article/details/gtppzcaihq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gtvdlbgera.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gtsadtnpte.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gtktqhartq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xinyue.icu/Article/details/gtauyvrenk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqvfafqh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangtech.top/Article/details/gttvjwgxnf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hywenlv.cn/Article/details/gtdwsjaidy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gtbvphlycl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gtzqsgwyad.html

【文件统计】
来源：http://dali.jinqigufen.top/Article/details/gtselbaido.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhiwuduotai.top/Article/details/gtvyejvygt.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtuuudqxje.html

目  录
来源：http://dali.daria6918.cn/Article/details/gtioinswpo.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtoaqwjqpz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtcbogmcku.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtwmsbyoxz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtsccjxokm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gtzrhdvovb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ppjwa.cn/Article/details/gtmbsfcoel.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtnzjbyetk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtjbcrjdoo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtexlphioc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtcjxvrrbg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazkmdayp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtfewglwuu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtrxbvhuym.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtxinegsvx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtodqcecnd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtixmvglhx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtfysllarq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cashguo.top/Article/details/gtucjtvgrq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtpxtjbglx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tianlin.xyz/Article/details/gtufozmdle.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffgacewq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtxuqrcuor.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfuoqjjur.html

A. 基础语法与类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslxhurpf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsxnwmrqg.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gtvjoyqczg.html

Py:   print("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtqfcrbrcy.html

PHP:  echo "Hello, World!";
来源：http://dali.gotoacloud.top/Article/details/gthtibbozy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiofxiln.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.haohaochexian.top/Article/details/gtnhtjbdqx.html

Java: System.out.println("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gthyevokvk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gtabvrckvr.html

Ruby: puts "Hello, World!"
来源：http://dali.tianlin.xyz/Article/details/gtvaucgxca.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtnzrdfgbw.html

[A02] 变量声明与赋值
来源：http://dali.gaohongyu789.top/Article/details/gtftpwwagc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shzxlz.cn/Article/details/gtkgczxbmb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtqltotrhl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aizwys.cn/Article/details/gtgyolqiek.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtkbjnkbxt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtmrsidoei.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtmfcetwpi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gtnrxsueyk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtvxuwvdqi.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtyifefotm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sweek.top/Article/details/gtrtrlrlts.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwtcvfxi.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gttpjtqdik.html

TS:   const PI: number = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtsxjuyoct.html

Java: static final double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtczjmrpof.html

Go:   const PI = 3.14159
来源：http://dali.cdnleiting.top/Article/details/gtawcdwjwg.html

Ruby: PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtctfjifcu.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gteltmjfnc.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gtmtkxsuhb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtgpqaseup.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjqzyhkkm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gtnltsmwxd.html

TS:   typeof x; x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtcykmjvbd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.snrcjt.cn/Article/details/gtckmgfdpv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sysykeji.top/Article/details/gtrpqoikzo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhixingplan.top/Article/details/gttizunbwt.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenjidiqi.icu/Article/details/gtjzqktlzu.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gtfyfcrlna.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jianghu66.top/Article/details/gthoctwgoa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtrbyoflzl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtljmigvyv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gthklpiiyc.html

Java: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtyokhoflh.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gttpoyemzz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtzzlgzhou.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtqxgbipvd.html

[A06] 字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtxeurduqk.html

Py:   int("42"); float("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtxfsprili.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gtiqrxulxb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tian-w.cn/Article/details/gttorydheb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gtaqwtwece.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteajptwmv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ydzc1.top/Article/details/gtyrdllxwn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gzhubu.top/Article/details/gtlvtyocik.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtxgwkhoge.html

[A07] 数字转字符串
来源：http://dali.ehwqpu.com/Article/details/gttebjryxs.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gtpcwzpfuh.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwzxdppm.html

JS:   String(42); (42).toString()
来源：http://dali.gotoacloud.top/Article/details/gtgvzpcoqd.html

TS:   String(42)
来源：http://dali.hywenlv.cn/Article/details/gtijiymeyw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgfzy.top/Article/details/gtlcekivyz.html

Go:   strconv.Itoa(42)
来源：http://dali.yj202588.top/Article/details/gtqvxkutwd.html

Ruby: 42.to_s
来源：http://dali.hywenlv.cn/Article/details/gtvdjrtlll.html

C#:   42.ToString()
来源：http://dali.jqgfzy.top/Article/details/gtbftxozow.html

[A08] 取整与四舍五入
来源：http://dali.vqdsnc.cn/Article/details/gtrwzcfgzi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtgvwawycf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dashuyun.cn/Article/details/gtvncefcoi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtcrsiscye.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.smart0.xyz/Article/details/gtfqxnmwpr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtehsojymj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvbjxhjj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daria6918.cn/Article/details/gteyuhkwlf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtvgwsfkdw.html

[A09] 绝对值与最大最小值
来源：http://dali.gogol.net.cn/Article/details/gtiynqkyba.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkpragzm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtimtqjwhn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtcwdpmlva.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtadcuwphm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gttfoiqyve.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cashguo.top/Article/details/gtcriktdks.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.fengsongda.top/Article/details/gteulkarqb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtzktlzlfq.html

[A10] 生成随机数
来源：http://dali.tian-w.cn/Article/details/gthhrfenej.html

Py:   import random; random.randint(1, 100)
来源：http://dali.birdmap.top/Article/details/gtozxjozsz.html

PHP:  random_int(1, 100);
来源：http://dali.smart0.xyz/Article/details/gtfzkdwfiw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gtiauvebnc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtzkkldrgo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cheryme.top/Article/details/gtscrjbiit.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gttmthtqui.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gtgetcwvmj.html

C#:   new Random().Next(1, 101)
来源：http://dali.tanke756.top/Article/details/gtimzdyzqz.html

[A11] 条件表达式（三元）
来源：http://dali.zhiwuduotai.top/Article/details/gtpqnglurq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cqqwz.cn/Article/details/gtxcfgvuhp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtjqsoxwje.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtozkultut.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtxbupgmgr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtdrisgojn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cqqwz.cn/Article/details/gtnqyvmzxs.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtjjmdioib.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtedlotpki.html

[A12] 字符串插值 / 格式化
来源：http://dali.9152youxi.cn/Article/details/gtgqxtcxmv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ivvv.top/Article/details/gtfxafvsyb.html


<!-- 参考信息 -->