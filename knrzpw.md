代发 wailian999

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtcdoogwwh.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtgdwzyepe.html

[U80] PHP：代码规范修复
来源：http://dali.wangshuangyany.cn/Article/details/gtlscxvaoc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gtjvlxtzcr.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gtvvkevrdm.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gtfjwggrnv.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gtxvmrlkoa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gzhubu.top/Article/details/gtflthhuxv.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gtgrfyjokg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtcpbfzmdz.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gthsvfleil.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gtereautfh.html

[U85] JS：可选链
来源：http://dali.ppjwa.cn/Article/details/gtnukqqhsn.html

a?.b?.c
来源：http://dali.0kj1m.cn/Article/details/gtazgrogsw.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtyyholtun.html

a ?? b
来源：http://dali.yj20258888.top/Article/details/gtgwqfrcdo.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gtrvpwlvwl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cheryme.top/Article/details/gtpnvacdnf.html

[U88] JS：对象展开合并
来源：http://dali.xuanzx.com/Article/details/gtkgfcjxpf.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraztyeav.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gtbmvapyqw.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtqjnkpsyj.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gteteewwws.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gttflnymjm.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258.top/Article/details/gtqydsntlx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.birdmap.top/Article/details/gtjoyihcfv.html

[U92] JS：深拷贝
来源：http://dali.daxiang520.top/Article/details/gtvjxzbpec.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtwfnbkkfz.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqilqtre.html

`共 ${n} 条`
来源：http://dali.yangfankeji.com/Article/details/gtztfmfluv.html

[U94] JS：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtnojxhhyl.html

const double = x => x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtnygbxxbv.html

[U95] JS：Promise 包装
来源：http://dali.cashguo.top/Article/details/gtszfhqxrf.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gtnbbtaaql.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gtsuhxvgkk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gttpluoubw.html

[U97] JS：并发请求
来源：http://dali.yanxiufei.cn/Article/details/gtwmbbjoez.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gttbwbqzec.html

[U98] JS：fetch 带 JSON
来源：http://dali.shzxlz.cn/Article/details/gtzinphamw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gtieotskwc.html

[U99] JS：事件监听
来源：http://dali.cucudq.cn/Article/details/gtmrhidbvq.html

el.addEventListener("click", e => {})
来源：http://dali.shzxlz.cn/Article/details/gtdgmqpjgr.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gtatrgvvot.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gtjrehpnbs.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gtgvtskdje.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gtzkhgxrdh.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gtlrafkwqw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dianchejie.cn/Article/details/gtaaljpuhz.html

[U103] JS：定时器
来源：http://dali.yuxming.cn/Article/details/gtygqopazc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yangfankeji.com/Article/details/gtwjjaolvu.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtzffzubuh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtcxonjiwd.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gtwxfflotk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gtkgwxaobo.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtbczqrbij.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.feifeiyinyue.top/Article/details/gthsfdgohc.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtczkdwegb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtfllgagrk.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gtihpkmits.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtyomftkfp.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gtlhsjtldd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtbpddoqtf.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gtbzciryhz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gtmsbptbma.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gtobbcwimd.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gtcgmnclyq.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gtaxusjznm.html

"7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtzahsfrzx.html

[U113] JS：正则替换全部
来源：http://dali.sxryk.cn/Article/details/gtqllwtree.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtejuspiql.html

[U114] JS：JSON 深比较
来源：http://dali.yuxming.cn/Article/details/gtuyahwnzq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gttqcketzu.html

[U115] JS：生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtpqvoelqi.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtkjjnbeme.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gtuzojzwce.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hnqzz.top/Article/details/gtskjmzget.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gtrwgtrnuz.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gtuaumuygp.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gtprbkmatg.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjpplmwa.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gtrefcwmhz.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gtbfsfklrg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gtcmxninhp.html

import.meta.env.VITE_API_URL
来源：http://dali.cashguo.top/Article/details/gtwruccdvm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjvucamlr.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gtdhlubplx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpqionyx.html

按语言统计（条）：
来源：http://dali.ehwqpu.com/Article/details/gtycqpajpe.html

Python ......... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtakrejnxs.html

PHP ............ 252
来源：http://dali.jinqigufen.top/Article/details/gtehgmmwgq.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gtdbskukaq.html

TypeScript ..... 212
来源：http://dali.yj20258888.top/Article/details/gtsgmoqrng.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtlonpvklu.html

Go ............. 212
来源：http://dali.tanke756.top/Article/details/gtykvnzdhn.html

Ruby ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtaatpmkre.html

C# ............. 212
来源：http://dali.redwolf501.top/Article/details/gtuxsbfvsg.html

C .............. 30
来源：http://dali.pengpengdd.cyou/Article/details/gtjhbqchhe.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gtgzyjqzlr.html

SQL ............ 90
来源：http://dali.dashuyun.cn/Article/details/gtowunrugw.html

Bash ........... 80
来源：http://dali.0kj1m.cn/Article/details/gtrkltjcwk.html

Kotlin ......... 15
来源：http://dali.cucudq.cn/Article/details/gtrnvwnobe.html

Swift .......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtftvsniat.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gtpmodbgoi.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gtwarsqthp.html

Scala .......... 10
来源：http://dali.snrcjt.cn/Article/details/gtoepytcbp.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtpiawgfto.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gtmixiqmcm.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gtricusgbj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtosiexacq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtaelvvlmh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtqndmltoh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gtrcdvgmdw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.9152youxi.cn/Article/details/gtidzwrhxf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtjsylqgzj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtyasznpgq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtkjshlcfi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtfarllcoj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtgoreizpe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtajyabohg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtnmnysccc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtierunxcw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtfnxeyjaj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ehwqpu.com/Article/details/gtqcganvyq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtlazukkou.html

Q SQL 专题                              90
来源：http://dali.tian-w.cn/Article/details/gthbwzpkhq.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gtrdsvmbln.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gtwpfsfbrb.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gtjuqnwams.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gtybqkvkew.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvenweav.html

合计                                  2106 条
来源：http://dali.yonumen.top/Article/details/gttbivruwh.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtsghtdbbn.html

使用提醒
来源：http://dali.zhongyouzk.top/Article/details/gtcblstzqu.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtybwiqmlu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gtbcbbuegc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtbzahwoog.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hongshengwenyu.top/Article/details/gtjguptihf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hywenlv.cn/Article/details/gtgylgbzai.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtepubwhic.html

—— 文件结束 ——
来源：http://dali.andypj.xyz/Article/details/gtufpnhhds.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcjgmcito.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gtiuzbwlzt.html

Common Programming Examples Cheat Book
来源：http://dali.nanxuanxn.top/Article/details/gtrberlpss.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrvtastvv.html

【收录内容】
来源：http://dali.nanxinkj.top/Article/details/gtamsdtkso.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sxryk.cn/Article/details/gtcilhzyie.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ehwqpu.com/Article/details/gtkcedtvno.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gtzqlkocxf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shangyingyoupin.top/Article/details/gtcrfrzwzb.html

【使用说明】
来源：http://dali.quarkkingdee.top/Article/details/gtnwjthecv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinghuilouyu.cn/Article/details/gtckfyvudx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cashguo.top/Article/details/gtbwjirbsz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pycfn.com/Article/details/gtdiehfnfg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jyoumei.cn/Article/details/gtbaorreoc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gtaqmcpoer.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gtsgsjnasz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhongyouzk.top/Article/details/gtvjfajiod.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.haohaochexian.top/Article/details/gtavlqqeaz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gtgibtaycm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258888.top/Article/details/gtxtjovnfm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.daxiang520.top/Article/details/gtywtmqlxg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.meibo888.top/Article/details/gtnsaadfua.html

【文件统计】
来源：http://dali.shanyushiyangtech.top/Article/details/gtczxziuvx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gtgwowbree.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtpovcnluu.html

目  录
来源：http://dali.zdqjudy.top/Article/details/gtmowhmsxr.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtuxybljro.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtmknihxrf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtzyxqubsu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtzrltfynd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtdqhbixiv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuanzhike.top/Article/details/gtjghqwpdj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsffxerif.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeogwzcv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gtfunuevyl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtjpahyzqf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gtlnmbzyvr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtdehudqmx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtdjhwwzrc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtpihtbkoa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtpmvtkzoo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj202588.top/Article/details/gtljhgcpwc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtjbmznxtx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtscccodyg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fzhhl.top/Article/details/gtvfurjvuh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ybcxt.top/Article/details/gtwgztkskf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtjffiggqe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtkiogvayy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiadeoueb.html

A. 基础语法与类型
来源：http://dali.ehwqpu.com/Article/details/gtjhaqepsc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrrhoytje.html

[A01] Hello World
来源：http://dali.jqgfzy.top/Article/details/gtmzqbxerl.html

Py:   print("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtrthqnpux.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesiabpiz.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtlvhqldhn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jlsjyb.cn/Article/details/gtkhcmombd.html

Java: System.out.println("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtnxmaopeg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtsoybcmge.html

Ruby: puts "Hello, World!"
来源：http://dali.xylfe.cn/Article/details/gtvsvbeddw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtwgmwkxak.html

[A02] 变量声明与赋值
来源：http://dali.nanxinkj.top/Article/details/gtqdxgrmtz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtoyibpdyb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daxiang520.top/Article/details/gtmnwpdnxu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtmfhxqqmc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gotoacloud.top/Article/details/gtcqxnvcvi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtiajmxmmn.html

Go:   name := "Alex"; age := 20
来源：http://dali.xinyue.icu/Article/details/gtqgbblmhc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gtffebhwfq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtmloblkfl.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gtaudzmhrt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hammf.cn/Article/details/gtifsreckj.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtqjplxfmi.html

JS:   const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtmfircinl.html

TS:   const PI: number = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtnobghlry.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtgducmlbd.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gtpaxejhqv.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtdwjawfzg.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckjsyfnn.html

[A04] 判断变量类型
来源：http://dali.meibo888.top/Article/details/gtvkaheych.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhongyouzk.top/Article/details/gtwhdjetgw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.redwolf501.top/Article/details/gtwvrkafha.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sweek.top/Article/details/gtiprjegnr.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtgocrsazy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nanxuanxn.top/Article/details/gtoqklubrv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhiwuduotai.top/Article/details/gtuigunpkg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkryylypn.html

C#:   x.GetType().Name; x is int
来源：http://dali.kuanghao11.cn/Article/details/gtytpawtet.html

[A05] 整数除法与取模
来源：http://dali.ydzc1.top/Article/details/gtuyxwgtff.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gtcqrvqnuv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtbfkvusde.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtrqauuorb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtpybzpwys.html

Java: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtpcqlbmad.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtiujkqqpv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtrskwgvjq.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtolbifshp.html

[A06] 字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtuirmeqxz.html

Py:   int("42"); float("3.14")
来源：http://dali.xuanzx.com/Article/details/gtwshjvxyt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gthewcmytt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaimteyxn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtintpjwhj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hammf.cn/Article/details/gtxfaloygg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gtbxwfzkxr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gtgiyxgeqm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guannengcc.top/Article/details/gtcncyeuqz.html

[A07] 数字转字符串
来源：http://dali.yj20258.top/Article/details/gtlybhtxzc.html

Py:   str(42)
来源：http://dali.ydzc1.top/Article/details/gtqkrlyfdz.html

PHP:  (string) 42; strval(42)
来源：http://dali.sweek.top/Article/details/gtogzioijp.html

JS:   String(42); (42).toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpwdscvj.html

TS:   String(42)
来源：http://dali.yuanzhike.top/Article/details/gtlbgvbwhi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aizwys.cn/Article/details/gtacsngpfk.html

Go:   strconv.Itoa(42)
来源：http://dali.zhixingplan.top/Article/details/gtmqjrgckf.html

Ruby: 42.to_s
来源：http://dali.xziqi.cn/Article/details/gtaxhgoqtd.html

C#:   42.ToString()
来源：http://dali.meibo888.top/Article/details/gtgtvgpula.html

[A08] 取整与四舍五入
来源：http://dali.mhx1999.top/Article/details/gtaqmyquvt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtekbrsnoo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hywenlv.cn/Article/details/gtbmerfptg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtarcasxyh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hongshengwenyu.top/Article/details/gtlybknimm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjmtkhnv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtaumldlfw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gtnnsxadrr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtimvlstrn.html

[A09] 绝对值与最大最小值
来源：http://dali.cucudq.cn/Article/details/gtwitopnet.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtrgotmlub.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtbemlahoz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gttqphyzmr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtmaqnirjh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtgnxuvfrc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ehwqpu.com/Article/details/gtasjyeaxt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pycfn.com/Article/details/gtpkawtqji.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtyedyeixk.html

[A10] 生成随机数
来源：http://dali.jlsjyb.cn/Article/details/gtnjcdjfje.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yueranfly.top/Article/details/gtbfpdaxfb.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gtywmzubvw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtlhpovahd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtdvffevpd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sweek.top/Article/details/gtervaghff.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tianlin.xyz/Article/details/gtrrcamvos.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gttjwvqram.html

C#:   new Random().Next(1, 101)
来源：http://dali.tian-w.cn/Article/details/gtwllstfya.html

[A11] 条件表达式（三元）
来源：http://dali.yj20258888.top/Article/details/gtnnqjtbbn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxinkj.top/Article/details/gtnmdttlyr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtcyhmuijg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtghcmolsm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtwiggegay.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzicuxvia.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fengsongda.top/Article/details/gtfcvgzoff.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtqkzhitrm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtxzpiiajv.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtbymndsut.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.pycfn.com/Article/details/gtsaykmglc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zdqjudy.top/Article/details/gtclambpla.html

JS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gtipsfpzpr.html

TS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gtbpovrajd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.meibo888.top/Article/details/gtrkiblzfg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.9152youxi.cn/Article/details/gttxrcngma.html

Ruby: "Hello, #{name}!"
来源：http://dali.aibaodan.cn/Article/details/gtaigcawsp.html

C#:   $"Hello, {name}!"
来源：http://dali.xylfe.cn/Article/details/gtfmszveha.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.snrcjt.cn/Article/details/gtshxubnno.html


<!-- 参考信息 -->