代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gtxugaiowm.html

parse_ini_file("config.ini", true)
来源：http://dali.wangdashe.top/Article/details/gteawihimc.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtqkiiyspn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gtsderlezg.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gtwyzkrrtm.html

composer require psr/container
来源：http://dali.hammf.cn/Article/details/gtlhjrquhq.html

[U76] PHP：简单路由
来源：http://dali.jyoumei.cn/Article/details/gtkmixumhn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gtibxcexze.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gtnxujnbxc.html

composer require twig/twig
来源：http://dali.hfpthk.cn/Article/details/gtvbgghgtk.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtodzzcatl.html

composer require --dev phpunit/phpunit
来源：http://dali.shzxlz.cn/Article/details/gtskifcdjw.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gtwdbpnwhs.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtzeitljlf.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gtyqlezuol.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pycfn.com/Article/details/gtmtmxbffy.html

[U81] JS：初始化项目
来源：http://dali.cdnleiting.top/Article/details/gtcycfqzxd.html

npm init -y;  npm i express
来源：http://dali.hysaishi.cn/Article/details/gtuhifkwxo.html

[U82] JS：package.json 脚本
来源：http://dali.hnxiangtu.top/Article/details/gtioeatckg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gtfzdhocup.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzggapco.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtymmwcwsn.html

[U84] JS：CommonJS 写法
来源：http://dali.feifeiyinyue.top/Article/details/gtlzglgkzo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgufenzy.top/Article/details/gtwqkfzpse.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gtcctdioot.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gtlsqfgmen.html

[U86] JS：空值合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtclzudvpe.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gtdggmqaek.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtgjfkyqym.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gtfpcsdviv.html

[U88] JS：对象展开合并
来源：http://dali.gotoacloud.top/Article/details/gtevxkplpr.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtvalwywyd.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gtllrdekdt.html

[...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtroeivvgx.html

[U90] JS：数字数组排序
来源：http://dali.xylfe.cn/Article/details/gttjilzqso.html

[...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtsxhcysfy.html

[U91] JS：对象键值遍历
来源：http://dali.iojbl.cn/Article/details/gtyuafucup.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gtkdveddsk.html

[U92] JS：深拷贝
来源：http://dali.9152youxi.cn/Article/details/gtrkgknmby.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtnpwjhzud.html

[U93] JS：模板字符串
来源：http://dali.cqqwz.cn/Article/details/gtwxtbynio.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gtdaagyvmu.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtlibileje.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtessoezvc.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gtptasvjfc.html

new Promise((resolve, reject) => {})
来源：http://dali.yuanzhike.top/Article/details/gtwqjbqzco.html

[U96] JS：async/await 与异常
来源：http://dali.xziqi.cn/Article/details/gtoqkqipoi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtukkqzpbe.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtcsxosvoj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtnzhetfnu.html

[U98] JS：fetch 带 JSON
来源：http://dali.xylfe.cn/Article/details/gtztnlqxqs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtlrbvzwps.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gtsazaayhp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gtspzjkecx.html

[U100] JS：DOM 查询
来源：http://dali.cdnleiting.top/Article/details/gtqlxyqmir.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gtpngbgnps.html

[U101] JS：classList 操作
来源：http://dali.tianlin.xyz/Article/details/gtegtkrqdg.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtfynflckx.html

[U102] JS：本地存储
来源：http://dali.zhengqikj.top/Article/details/gtpdgfotdz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gtiaqvyrqw.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtbjgcbisc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.feifeiyinyue.top/Article/details/gtehcahycv.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gtlzosshaq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtxlfbqyxc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtitjpnubx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.meibo888.top/Article/details/gtblgmslnf.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtafxanpqo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shzxlz.cn/Article/details/gtkqedudey.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtzkenptfu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtgvtdtilo.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gtehtzjqsj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtkvpaxbzv.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gtcufkdegj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrffpyawe.html

[U110] JS：数组分块
来源：http://dali.hywenlv.cn/Article/details/gtsmiwfikq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gtbbqebocd.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gtgstpvoud.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtispyogpx.html

[U112] JS：字符串补位
来源：http://dali.jinqigufen.top/Article/details/gtlsymyzoz.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtmtolgbfr.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gtfgmknniw.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtyxpjfsgf.html

[U114] JS：JSON 深比较
来源：http://dali.fzhhl.top/Article/details/gtnlkiukuq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtgkuhhgqt.html

[U115] JS：生成 UUID
来源：http://dali.yonumen.top/Article/details/gtxwyaukfj.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtohysdnwb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtzwqmogxq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmzlkdwvw.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtoltytosh.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gtapkkuifw.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gtqkqbozmc.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gthnyvooky.html

[U119] JS：生产构建
来源：http://dali.aibaodan.cn/Article/details/gtljkhnlru.html

npx vite build
来源：http://dali.ybcxt.top/Article/details/gtkysgraii.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gtgpcopjyf.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gtkocuofbx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtphditdua.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gtiedhotjt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmevfsbru.html

按语言统计（条）：
来源：http://dali.sysykeji.top/Article/details/gtrgtmnwoj.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gteqazlrsf.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gtdqtihssz.html

JavaScript ..... 252
来源：http://dali.sxryk.cn/Article/details/gtjelcpcjj.html

TypeScript ..... 212
来源：http://dali.jlsjyb.cn/Article/details/gtuaygverk.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gthugytbiq.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtczjhqorn.html

Ruby ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtplodslsg.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtqitpdlop.html

C .............. 30
来源：http://dali.jiagoushi.top/Article/details/gtayeitfqu.html

C++ ............ 30
来源：http://dali.gaohongyu789.top/Article/details/gtlwxpunmm.html

SQL ............ 90
来源：http://dali.dashuyun.cn/Article/details/gtncxqhjrt.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdotlisex.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtytuyujls.html

Swift .......... 15
来源：http://dali.ppjwa.cn/Article/details/gtxxebojba.html

Lua ............ 10
来源：http://dali.zhiwuduotai.top/Article/details/gtgryehvfg.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtmcqznafa.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gthoyaawzz.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtmhxbrbwn.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgahnisk.html

按章节统计：
来源：http://dali.guannengcc.top/Article/details/gtlmfdocbq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtclfdcgxi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtzecuolsp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtxqysfloj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtmsambevi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gteidhaatq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gttbmtbglw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtlbrtgfyl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtfsopvork.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtowdhecxt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gtqtjruklj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtowbkjynb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtzxxqqqfh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtqrbxsmoj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtloyjbcaq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gtwtzcrjum.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtdwlkdumx.html

Q SQL 专题                              90
来源：http://dali.yj202588.top/Article/details/gtnzanhyit.html

R Bash 专题                             80
来源：http://dali.xziqi.cn/Article/details/gtscjtheqe.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtmmniykbp.html

T 其他语言补充                          60
来源：http://dali.yuxming.cn/Article/details/gtdaikeiac.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gtgwkeeoun.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gttleysjce.html

合计                                  2106 条
来源：http://dali.gotoacloud.top/Article/details/gtlhnwsnks.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtnnrfjiur.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gtmwqakgld.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtvdhaqeio.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.birdmap.top/Article/details/gtysfllybi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.c1oappe.top/Article/details/gtzymxddsz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jiagoushi.top/Article/details/gtayquuysz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtjqhuooys.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gtlginnbnr.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gttsjeujxi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteutmhoqu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gthhkwhkpo.html

Common Programming Examples Cheat Book
来源：http://dali.pycfn.com/Article/details/gtlrsndvff.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyccqiyxy.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gtfmfosjji.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwllmzdra.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gtwcynxqsl.html

SQL · Bash · C · C++
来源：http://dali.zhengqikj.top/Article/details/gtbuedxlvu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jyoumei.cn/Article/details/gttohuawiz.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gtttvzxwsg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shangyingyoupin.top/Article/details/gtpqdonvpn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyfxepka.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gtmykypiqn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhiwuduotai.top/Article/details/gtusvkoyik.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gtsjvckaeg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtiptweshf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hongshengwenyu.top/Article/details/gtnqjnmcyp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gttuwltqqs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuxming.cn/Article/details/gthlshruqn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gtkqotsyfv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.birdmap.top/Article/details/gtnwwhvxjq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gtkactmmhq.html

【文件统计】
来源：http://dali.andypj.xyz/Article/details/gttyiykfcf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcppssnsb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtuydzzcee.html

目  录
来源：http://dali.aizwys.cn/Article/details/gtbhnvhxcr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gthxdeagem.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gtqwkdmxxu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtulpzybrv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtkdsojigx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gtwjgeihjf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yvedp.cn/Article/details/gtjjezsvou.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtoxqqsxft.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gteakpzsfq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtfiiignme.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpikqecsk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtgukvhzoa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtwaqelfqj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtkszidtow.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtcmfnegva.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtssktabrz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhoulong.xyz/Article/details/gtpwejodwk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtukjxcvna.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtwtvgsmit.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtjnqlpsxy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ydzc1.top/Article/details/gtajvtbupj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtfdtlozsc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtwaarrqkg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtptudfqwx.html

A. 基础语法与类型
来源：http://dali.c1oappe.top/Article/details/gtknhnqthq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtslnkpnjp.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtttlimjbm.html

Py:   print("Hello, World!")
来源：http://dali.wangdashe.top/Article/details/gtwzfpbamw.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gtejlcadxc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtrgtzrtyn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gtbbynvyjk.html

Java: System.out.println("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtxevbmmep.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtqnecoxab.html

Ruby: puts "Hello, World!"
来源：http://dali.wangshuangyany.cn/Article/details/gtkczuebyn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtxoaehaww.html

[A02] 变量声明与赋值
来源：http://dali.jqgufenzy.top/Article/details/gtmaoqwbkn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dashuyun.cn/Article/details/gtrshmshnt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtdkomlnuc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.havefunace.top/Article/details/gteyszsali.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hammf.cn/Article/details/gtvqiksrmq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtolbepsmj.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gtflbyjhuq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.9152youxi.cn/Article/details/gtkpntkmrp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtxaofahzo.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gtancbcaiy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gtetwtruby.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtaqikpkhl.html

JS:   const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtlgbdvmrj.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtapmgdcfh.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtyqwoezgt.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gtbfeicnjf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtboxiqqfz.html

C#:   const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojzdvtgc.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtazjtqdoz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258.top/Article/details/gtgblvmfmh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuxming.cn/Article/details/gtnterkfud.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtepzqmryc.html

TS:   typeof x; x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gtifknjjlg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dianchejie.cn/Article/details/gthbhqqhjm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gtxlejoafp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsubzhjh.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtwwcrjtbu.html

[A05] 整数除法与取模
来源：http://dali.yj20258888.top/Article/details/gtpdhkpcan.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gtiqbfuhxa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtumyligkp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtnamwjbgu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtvncweuzd.html

Java: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtexsagxzv.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtjojidzqs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtiikpymla.html

C#:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtcvseqlpe.html

[A06] 字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtqccekysf.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gtoxjztegu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gogol.net.cn/Article/details/gtaegrbtgq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gtckwxocrl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gtponfkjmq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guannengcc.top/Article/details/gtdzwfnfwp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aibaodan.cn/Article/details/gtfktzhnnj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gogol.net.cn/Article/details/gtzibcsorq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gtuogdwenh.html

[A07] 数字转字符串
来源：http://dali.yueranfly.top/Article/details/gtewmpoals.html

Py:   str(42)
来源：http://dali.quarkkingdee.top/Article/details/gtgmzssecw.html

PHP:  (string) 42; strval(42)
来源：http://dali.redwolf501.top/Article/details/gtyksonsvp.html

JS:   String(42); (42).toString()
来源：http://dali.jinqigufen.top/Article/details/gtecscaqck.html

TS:   String(42)
来源：http://dali.jiagoushi.top/Article/details/gtjqrwizbp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daria6918.cn/Article/details/gtkaegppjx.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigfzy.top/Article/details/gtzngeandj.html

Ruby: 42.to_s
来源：http://dali.iojbl.cn/Article/details/gtuuuauzch.html

C#:   42.ToString()
来源：http://dali.wangdashe.top/Article/details/gtjzlphyzy.html

[A08] 取整与四舍五入
来源：http://dali.zycfv.cn/Article/details/gtjzpfsuwl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtoobagiyo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yueranfly.top/Article/details/gtbgntfgqd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtesqemthz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.bjfxy.top/Article/details/gtypwlxaji.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtyaetcpdb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtjtdirrhy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sufxvd.cn/Article/details/gtbpchvqqq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtngjknyhk.html

[A09] 绝对值与最大最小值
来源：http://dali.ivvv.top/Article/details/gtdkkkxdqj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtzylhpmkc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtklkqnrtn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtzmmkywoz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtiqvkmnqu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hammf.cn/Article/details/gtmimtdrjf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gaohongyu789.top/Article/details/gtaywoxecr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jlsjyb.cn/Article/details/gtvlqmxaeo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtkohqqxnt.html

[A10] 生成随机数
来源：http://dali.c1oappe.top/Article/details/gtpbcbabwa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.316326.xyz/Article/details/gtvoivkhjm.html

PHP:  random_int(1, 100);
来源：http://dali.zhoulong.xyz/Article/details/gtxwzmdxni.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtpqleoowj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgfzy.top/Article/details/gtzlqaimgh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gtksheqzjb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dianchejie.cn/Article/details/gtblbkndme.html

Ruby: rand(1..100)
来源：http://dali.yvedp.cn/Article/details/gtjgjqqood.html

C#:   new Random().Next(1, 101)
来源：http://dali.bjfxy.top/Article/details/gtzvyvojvm.html

[A11] 条件表达式（三元）
来源：http://dali.nwbrower.top/Article/details/gtgwwaocul.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhixingplan.top/Article/details/gtcsgyjcbd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gteeeqdlkg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtvhehjcbl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtwuzvgigc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtmpsvvdhm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenlongwang.top/Article/details/gtqgvkprqf.html


<!-- 参考信息 -->