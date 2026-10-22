代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.kuanghao11.cn/Article/details/gtuiosmcme.html

composer require psr/container
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtvapscj.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gtdseecyvk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gtdmucljoc.html

[U77] PHP：模板渲染
来源：http://dali.cashguo.top/Article/details/gtszcnhahi.html

composer require twig/twig
来源：http://dali.shuidangran.top/Article/details/gthzbqqper.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtucsviyfm.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgufenzy.top/Article/details/gtzsjxuwha.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gtvbrsylfk.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gtiukxsnbv.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258888.top/Article/details/gtjwbtntqr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zycfv.cn/Article/details/gtelqeyczo.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gtyyyawtop.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gtmbbnwxoh.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxhrqeqd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gtvermoovc.html

[U83] JS：ES Module 导入导出
来源：http://dali.hysaishi.cn/Article/details/gtiygwnpgo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtccbzplsv.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gtdwkelvoa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gtzdkwdowo.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gtmkdzqycg.html

a?.b?.c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncgkunlx.html

[U86] JS：空值合并
来源：http://dali.fengsongda.top/Article/details/gtfqmbfhkk.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtefwdmwid.html

[U87] JS：解构默认值
来源：http://dali.wangdashe.top/Article/details/gthtfdysdr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cashguo.top/Article/details/gtkeerfkrk.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gtpqzmxrlb.html

{ ...a, ...b }
来源：http://dali.guannengcc.top/Article/details/gtuoqpzmsg.html

[U89] JS：数组去重
来源：http://dali.yuxming.cn/Article/details/gtlyogmiyq.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtpgjtrkhk.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpdgxjby.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtbbsvlwbw.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtsdnoeqaw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gthjnwxxne.html

[U92] JS：深拷贝
来源：http://dali.sweek.top/Article/details/gtxwzbmtos.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmmjyqfml.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtikfraslq.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gtokgvhqgd.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtultgqpgj.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtlymcvglk.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gtjbxoeltr.html

new Promise((resolve, reject) => {})
来源：http://dali.guannengcc.top/Article/details/gtasjvgtfu.html

[U96] JS：async/await 与异常
来源：http://dali.wangshuangyany.cn/Article/details/gtwktacrin.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtqsexvrcq.html

[U97] JS：并发请求
来源：http://dali.wangshuangyany.cn/Article/details/gtltixvwmx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtyqsotuoy.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gtzhnzgsex.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrokqwee.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gtrlipzqkn.html

el.addEventListener("click", e => {})
来源：http://dali.snrcjt.cn/Article/details/gtkzunhnbv.html

[U100] JS：DOM 查询
来源：http://dali.c1oappe.top/Article/details/gtjuiiozpf.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gtryannmjv.html

[U101] JS：classList 操作
来源：http://dali.pengpengdd.cyou/Article/details/gtfrdxvnjj.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtudtjlwdo.html

[U102] JS：本地存储
来源：http://dali.9152youxi.cn/Article/details/gtypobvpth.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gtypcjgokg.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gtybdjfnjx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtskzfdavx.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtamxdamls.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtpubsquce.html

[U105] JS：节流
来源：http://dali.zhengqikj.top/Article/details/gtybmtvbgs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhixingplan.top/Article/details/gttymdhgoq.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtyeugvrzx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtisymnltc.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtgklisdur.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtdztzxlyb.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gtzsthjlkj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sweek.top/Article/details/gtcgzerkfh.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gtqchpwjis.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtyxhnvpjl.html

[U110] JS：数组分块
来源：http://dali.haohaochexian.top/Article/details/gtscqtjwwq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gtxobxesoq.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtqvvyffew.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtsimluzzy.html

[U112] JS：字符串补位
来源：http://dali.xuanzx.com/Article/details/gtaudgkxpo.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtoxiibhiz.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gtjvgsvijm.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtqfkyyagg.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gtuyfdiibp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtkwnxfezx.html

[U115] JS：生成 UUID
来源：http://dali.tanke756.top/Article/details/gtozpdjlyp.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtkcrliniv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gtejekpoxe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdfbxcitr.html

[U117] JS：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtgbzmnwcq.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gtdzspgwdf.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtetdetqsd.html

npm i -D vite;  npx vite
来源：http://dali.sweek.top/Article/details/gttqojhvnc.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gtjlilaxpw.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gtnvnczpdq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gtadgklzwg.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gthquwkegs.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcnfjsoai.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gtiqdogxdf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtaionkgcv.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gtmocuwcjx.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gtyjnmxlgh.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gtuhjlqxbl.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gtsxrrreek.html

TypeScript ..... 212
来源：http://dali.tian-w.cn/Article/details/gtdedgkocy.html

Java ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtqtfhcrpq.html

Go ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtjcflojvw.html

Ruby ........... 212
来源：http://dali.iojbl.cn/Article/details/gtmzarusnh.html

C# ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtyzxnaytt.html

C .............. 30
来源：http://dali.jyoumei.cn/Article/details/gthcpedmql.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gttznuugnv.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gtmgnzmxvm.html

Bash ........... 80
来源：http://dali.sxryk.cn/Article/details/gtbqpbhyop.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gtxpesshex.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtcgewwnhi.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gtpdxwleoc.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtatxlswob.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gtznbtauve.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtnlbnzhqm.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxlcqubq.html

按章节统计：
来源：http://dali.sufxvd.cn/Article/details/gtuwnqfrch.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gteuynslwn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gttnrqrtcl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtezjcvrht.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtteevqzxd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gtfykybbyj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtcxaksqis.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtjmgmfxig.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gtfelrgirx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtlbfakrul.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gtxbppdovu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtbprkfatl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtakvopwmr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtorbccvag.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gthyjupiuy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gtkowzzvjp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidddxqga.html

Q SQL 专题                              90
来源：http://dali.feifeiyinyue.top/Article/details/gtyvgaxfil.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gtahmcwmbc.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gtglxqjhqa.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gtqansrabs.html

U 高频实用片段                         120
来源：http://dali.cashguo.top/Article/details/gtnjqjuaxx.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfqjhipp.html

合计                                  2106 条
来源：http://dali.birdmap.top/Article/details/gtmltmxdkw.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtuaxzjgzd.html

使用提醒
来源：http://dali.9152youxi.cn/Article/details/gtntgwusmc.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gthlcwrclj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gttprkzklo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.birdmap.top/Article/details/gtmzkvvlrs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gttrdanoyr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtyesvqymc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.bjfxy.top/Article/details/gtreyatrvy.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gtoojttscg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttnppvprt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gtokppmtun.html

Common Programming Examples Cheat Book
来源：http://dali.cashguo.top/Article/details/gtebgbkqvs.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkndmqoam.html

【收录内容】
来源：http://dali.tanke756.top/Article/details/gtxpyersil.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nwbrower.top/Article/details/gtpvbltrta.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gttmasqjxs.html

SQL · Bash · C · C++
来源：http://dali.ydzc1.top/Article/details/gttkwlgnmv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gticrmysch.html

【使用说明】
来源：http://dali.quarkkingdee.top/Article/details/gtcnbxskoc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daxiang520.top/Article/details/gtmelhgdlo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtnhjahmyc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yanxiufei.cn/Article/details/gtrdmqgown.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gtmttokmqn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.andypj.xyz/Article/details/gthgfveyjx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigfzy.top/Article/details/gtspwgprxz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnqzz.top/Article/details/gtyhrxzhel.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gtghkpvoyl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gtcwmslcmu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqizbwcr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ybcxt.top/Article/details/gtdsgdveep.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zdqjudy.top/Article/details/gtdtiazrfn.html

【文件统计】
来源：http://dali.dianchejie.cn/Article/details/gtbnhjsgcs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gtoshszkvw.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtbpwehzdo.html

目  录
来源：http://dali.hywenlv.cn/Article/details/gtrdsxfdff.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtndpmqbee.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtpvuxsvgv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtwarbrngt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtbtbfxnko.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gtlwzaojvj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gttmcdednb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtijkytsmz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtegojogsn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtbxdcvtuk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtdhlrajnr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gteqajnybs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtyahoruka.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtnkkszpuu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtmeyvvnhw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gtpbgzsvxa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gtfmsfbath.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gttswfgfnq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtcqbtbgkm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.316326.xyz/Article/details/gtezfpkzon.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangdashe.top/Article/details/gtgnwhqyyz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtqkjyzehx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtsfehumps.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyguhlyul.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gtrdxwjvru.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyrndrefa.html

[A01] Hello World
来源：http://dali.jyoumei.cn/Article/details/gtcebcjjry.html

Py:   print("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgevbfhdt.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gtlpojpvbz.html

JS:   console.log("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtixgiffzn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangtech.top/Article/details/gthxgjuuxz.html

Java: System.out.println("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtcowgzdch.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtsqijausd.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwljupfp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtbwqyhgji.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetwnektw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtokgduxkp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yonumen.top/Article/details/gtahabsxiz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hammf.cn/Article/details/gtazrlwozn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hammf.cn/Article/details/gtmncggsld.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtwoastwbb.html

Go:   name := "Alex"; age := 20
来源：http://dali.ehwqpu.com/Article/details/gtrldwioit.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gteqbxxkzh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtftcnbesv.html

[A03] 常量定义
来源：http://dali.zycfv.cn/Article/details/gtrvnveurn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtkgrwinzf.html

PHP:  const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtkjjqfhca.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtkdmwtsty.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtwjfwelrx.html

Java: static final double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtilehvigf.html

Go:   const PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvyqufsv.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngcvnjwr.html

C#:   const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtpzmwmyjo.html

[A04] 判断变量类型
来源：http://dali.jqgfzy.top/Article/details/gtmphdojdx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtdqwxgxkz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gtmaytvqce.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtvtowozig.html

TS:   typeof x; x instanceof Date
来源：http://dali.sweek.top/Article/details/gtvdnnsdey.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xziqi.cn/Article/details/gtvtbsowfy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sxryk.cn/Article/details/gtagbibkek.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gtrkpxpuid.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtvqoqplrf.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gtxqjznkmf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gotoacloud.top/Article/details/gtpfhzgyrc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtylmlwnle.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtujahszog.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gttwmizaak.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtkuxmomic.html

Go:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtcihudgdt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtbczgmhga.html

C#:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtwbgsuqhg.html

[A06] 字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtqeinrlmy.html

Py:   int("42"); float("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtldfaoalf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtngydhcpa.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuxming.cn/Article/details/gtngyrwyxz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gtliywwcfv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yongpay.top/Article/details/gtespstlkd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkmavant.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.snrcjt.cn/Article/details/gttuomcqfm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjhkcqzj.html

[A07] 数字转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtvcqskoay.html

Py:   str(42)
来源：http://dali.ppjwa.cn/Article/details/gtqiczvlsg.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetjsqwsg.html

JS:   String(42); (42).toString()
来源：http://dali.yanxiufei.cn/Article/details/gtxiteuqkc.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gtvewcckfk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hammf.cn/Article/details/gtpcbjixks.html

Go:   strconv.Itoa(42)
来源：http://dali.hnqzz.top/Article/details/gteqqsksop.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gtzrnmbqvc.html

C#:   42.ToString()
来源：http://dali.zdqjudy.top/Article/details/gtgoakyqfs.html

[A08] 取整与四舍五入
来源：http://dali.haohaochexian.top/Article/details/gtsnpqavws.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gthqepzkqk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.snrcjt.cn/Article/details/gtltfvmley.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtmzelkugn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwchwres.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gttddagkbl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gtrxlcbeus.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ppjwa.cn/Article/details/gtdlfzeimt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtwymipulc.html

[A09] 绝对值与最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwccngsmk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbvajkky.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtzetbfhih.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtekcehiqo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtiujmhulg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziachzxd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gotoacloud.top/Article/details/gtvyuwgmnu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jqgfzy.top/Article/details/gtcynhfryj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtejkobtmp.html

[A10] 生成随机数
来源：http://dali.hywenlv.cn/Article/details/gtegyfedkd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gtnimhflzp.html

PHP:  random_int(1, 100);
来源：http://dali.quarkkingdee.top/Article/details/gtixxzhrkr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtsqbtjxgo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yongpay.top/Article/details/gtpicrdher.html

Java: new Random().nextInt(100) + 1
来源：http://dali.9152youxi.cn/Article/details/gthupeosiy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yanxiufei.cn/Article/details/gtqgfelscv.html

Ruby: rand(1..100)
来源：http://dali.pycfn.com/Article/details/gtepenkjyf.html

C#:   new Random().Next(1, 101)
来源：http://dali.svipenyu.cn/Article/details/gtadtucaah.html

[A11] 条件表达式（三元）
来源：http://dali.sxryk.cn/Article/details/gtsxxcgaql.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.316326.xyz/Article/details/gtvkdnzmzj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtnczrksjz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtlnoeljgo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtqcubjycz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtfdgyzglw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shangyingyoupin.top/Article/details/gtppwiejce.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtmepvnqte.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtkysupwsd.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosmblshl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.mhx1999.top/Article/details/gtzvvjtygb.html


<!-- 参考信息 -->