代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gtlywzztlx.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtpqhzzjil.html

[U72] PHP：写错误日志
来源：http://dali.nwbrower.top/Article/details/gtctksclik.html

error_log("失败: " . $e->getMessage());
来源：http://dali.snrcjt.cn/Article/details/gtcxetxunb.html

[U73] PHP：读取 ini 配置
来源：http://dali.nwbrower.top/Article/details/gtstmuewva.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhtzjlrm.html

[U74] PHP：读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtcydymyjf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.birdmap.top/Article/details/gtywkcdozt.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gtvbpaxosz.html

composer require psr/container
来源：http://dali.guannengcc.top/Article/details/gtxoxbqjhn.html

[U76] PHP：简单路由
来源：http://dali.yonumen.top/Article/details/gtdwbwiaui.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gtwdcebwjs.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtkhpdxwyv.html

composer require twig/twig
来源：http://dali.yangfankeji.com/Article/details/gtldfweibl.html

[U78] PHP：单元测试
来源：http://dali.hysaishi.cn/Article/details/gtikgezeiu.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gtfmorcghf.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtjjzdgsdh.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gtxzgejdln.html

[U80] PHP：代码规范修复
来源：http://dali.zdqjudy.top/Article/details/gtvxtawndw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gtblsqpvjq.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gtnpzmtppm.html

npm init -y;  npm i express
来源：http://dali.cdnleiting.top/Article/details/gtnldlxcrz.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvezdflm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ehwqpu.com/Article/details/gtlcgcxffd.html

[U83] JS：ES Module 导入导出
来源：http://dali.xinyue.icu/Article/details/gtnzgriwyo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtgjdkrujy.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbvkvmse.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.iojbl.cn/Article/details/gtvyaeqcqg.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gtkwnjtbfd.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gtppxacjtz.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gttnyariew.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtveijsade.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gtbglmqyct.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gtmqrgvshf.html

[U88] JS：对象展开合并
来源：http://dali.gotoacloud.top/Article/details/gtxqmhggul.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gtttwnbbcb.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gtolnvtito.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtgluranra.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiofbjcg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtegpadgma.html

[U91] JS：对象键值遍历
来源：http://dali.zhoulong.xyz/Article/details/gtwtovuioi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gtcfrtafkv.html

[U92] JS：深拷贝
来源：http://dali.hfpthk.cn/Article/details/gthamxuslc.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtdywwycyv.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gtiygyuzri.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gtidxzazun.html

[U94] JS：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtbwmoynxx.html

const double = x => x * 2;
来源：http://dali.cashguo.top/Article/details/gtbeedklzy.html

[U95] JS：Promise 包装
来源：http://dali.c1oappe.top/Article/details/gthecysghe.html

new Promise((resolve, reject) => {})
来源：http://dali.hnqzz.top/Article/details/gtgkanjxcg.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gtyyxfupmq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtppaccjlj.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gtjweyoaya.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtvzupoppm.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gtbncneofk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuetiantiany.cn/Article/details/gtgqlbqwvb.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gtaxzirxsl.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gtokvcxcge.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gtwswohsmn.html

document.querySelector(".item")
来源：http://dali.hfpthk.cn/Article/details/gtwmaxkrrl.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtvwcfurel.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gtkapuantu.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gtffgmajch.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj202588.top/Article/details/gtjosakdvc.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gtrbgovsaq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fzhhl.top/Article/details/gtvlbhflin.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtgdugprtc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtjqdbejmg.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtrqkaeaqf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gtlnaaniiw.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtliotpncu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgufenzy.top/Article/details/gtqkzqbenz.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gtpycaxdas.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtcgxlhons.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gtfhhmoxlr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnmudrhr.html

[U109] JS：数组分组
来源：http://dali.hfpthk.cn/Article/details/gtvyxulxwk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtgdffavsm.html

[U110] JS：数组分块
来源：http://dali.fzhhl.top/Article/details/gthpnppnqt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtqxyyyfyq.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gtoneypbqb.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gtsmjfjwdu.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gtrsniztpv.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtvsweyqym.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gtvibkzyld.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtdjqbdhxo.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gthixwrjhv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtswqwlxxx.html

[U115] JS：生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtbdrkljmu.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtlxeompsa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.316326.xyz/Article/details/gtlxxaevyp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtxyvxwjkk.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtfkwzlkum.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gtiksyszah.html

[U118] JS：开发服务器
来源：http://dali.ppjwa.cn/Article/details/gtotwxqaby.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtbzayoach.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gtlbzjcrol.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gtfyvvqbhe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtpbcgzzgj.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gtsuwaqcmq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gturkrfnyt.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpngnevw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gteehsgagu.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gthpytrsfh.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gtetfolcfn.html

PHP ............ 252
来源：http://dali.yj20258.top/Article/details/gtyyzvyrjm.html

JavaScript ..... 252
来源：http://dali.ehwqpu.com/Article/details/gteslywiit.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gtqfwwwova.html

Java ........... 212
来源：http://dali.bjfxy.top/Article/details/gtvernzqzh.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gttjmcuunu.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gtepbrgqhh.html

C# ............. 212
来源：http://dali.yangfankeji.com/Article/details/gtzlczposr.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomeqwhvv.html

C++ ............ 30
来源：http://dali.xinyue.icu/Article/details/gtyswzxvpk.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtjbpjzyax.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gtsynvvred.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtuygkwwij.html

Swift .......... 15
来源：http://dali.pycfn.com/Article/details/gtphdbayvm.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gtvnajobql.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtgcdradly.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gthvxkgerk.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtrqynfmkj.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gtazqvcbsx.html

按章节统计：
来源：http://dali.jinqigufen.top/Article/details/gtiltsdent.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtsbdyotkl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtfzfpojgg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtsghwngpd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gtemzbwcxl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtmaufhqej.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtriiveeea.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtoiupyjuv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtteuucsga.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtidwzdynk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtstsgyfck.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtpgomwhbd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtaaxpsouw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtwxrmoikw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchnxekui.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gtfeynqvny.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtbfvafaia.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gtlzznhdup.html

R Bash 专题                             80
来源：http://dali.yj20258888.top/Article/details/gtkwipohnz.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gtsdeydnwo.html

T 其他语言补充                          60
来源：http://dali.yj20258.top/Article/details/gtkzrmkslf.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gtwwxghbjj.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtnfoxrjuz.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gtdovnsteo.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtichldpbf.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gtsnjumwuq.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtfuivvofn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gtmphihizc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtaowxlzda.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gtpiqulqyk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtmaxoowws.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gtfbrymorh.html

—— 文件结束 ——
来源：http://dali.dianchejie.cn/Article/details/gtsrfpopck.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcmynusjd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sweek.top/Article/details/gtkkepzcau.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gtmpnyuegw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcrocffbp.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gtkuqdqqob.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gtiunmcdbh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gtqoxzrlmf.html

SQL · Bash · C · C++
来源：http://dali.bjfxy.top/Article/details/gtwtzqetsp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gtqmpdtern.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtduqamxqk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shangyingyoupin.top/Article/details/gthopejltd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gtvjsjlkiq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwileexq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnvgmryh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnxiangtu.top/Article/details/gtopoeledc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gtevbzuhtv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqswowsar.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daxiang520.top/Article/details/gtoukrjdxw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinghuilouyu.cn/Article/details/gtstkexxfl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gotoacloud.top/Article/details/gtgojfevpx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shuidangran.top/Article/details/gtghnlxcri.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuanzhike.top/Article/details/gtezzkikhb.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gtmxmwmqec.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gtgwxpcevc.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclpbstto.html

目  录
来源：http://dali.havefunace.top/Article/details/gtmotjezsb.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtonbkezld.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtcqjqyghs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtdmwkzmrv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtpohodqmp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtnxxtdqva.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gteznyuvfi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gtppnnkjbv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtkyhlxqbf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gtzdcbxsct.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzkkahhk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtgxrxelnk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtbfvtxrxm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtenmnpriu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtinzrfxzy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtnutpvrxj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gtxtvvqodk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxoxikks.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.dashuyun.cn/Article/details/gtrscdgffi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tianlin.xyz/Article/details/gtrmhnhshq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daria6918.cn/Article/details/gtqinzrcpl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtvixckowq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzqhwlqj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjbozgvje.html

A. 基础语法与类型
来源：http://dali.cqqwz.cn/Article/details/gtvtfakzgt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdbtstwyt.html

[A01] Hello World
来源：http://dali.gotoacloud.top/Article/details/gtbamqdaor.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtenfpinih.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gtbhvsxhlf.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtsfcppjpg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gtznnxzrtz.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtcotiudku.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gtbcgxzcrw.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gtkfolwyao.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtgszqhzrd.html

[A02] 变量声明与赋值
来源：http://dali.fzhhl.top/Article/details/gtxvztmvzv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtkntsmazf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.316326.xyz/Article/details/gtapxecspb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrhyxvzp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ivvv.top/Article/details/gthbftecpr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gtodzneyvg.html

Go:   name := "Alex"; age := 20
来源：http://dali.jyoumei.cn/Article/details/gtqlzonuxx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sxryk.cn/Article/details/gtyhtlhmdf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtwgwkmgvl.html

[A03] 常量定义
来源：http://dali.hnxiangtu.top/Article/details/gtdpqkczrr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gtafmnojgs.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtstpqpyaq.html

JS:   const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtxxejrtif.html

TS:   const PI: number = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtjegarxfb.html

Java: static final double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtfvmduevt.html

Go:   const PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gtjbipkgiz.html

Ruby: PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gttfxjheee.html

C#:   const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtmnuajjlp.html

[A04] 判断变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtlkdfcdym.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlgddufq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guowangkeji.top/Article/details/gtjrjdoybi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gtretwzzec.html

TS:   typeof x; x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gthgbkgery.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cashguo.top/Article/details/gtigurulmu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zdqjudy.top/Article/details/gtbxjuuguv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtogdkvzkr.html

C#:   x.GetType().Name; x is int
来源：http://dali.havefunace.top/Article/details/gtglcrnydl.html

[A05] 整数除法与取模
来源：http://dali.shuidangran.top/Article/details/gtpxvwfufe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gaohongyu789.top/Article/details/gtsjgjmanv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtujypcffe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtcjbilxol.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtcobuevmh.html

Java: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gthfguynxh.html

Go:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gttfvagtmr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtbbeytvok.html

C#:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtjjhzizxl.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtpiszmwdk.html

Py:   int("42"); float("3.14")
来源：http://dali.redwolf501.top/Article/details/gtkkixmkfc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ppjwa.cn/Article/details/gtzlgbnuyk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gzhubu.top/Article/details/gthhiactyt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtwxpkkmgr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtyzyholol.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuxming.cn/Article/details/gtfvikrawp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhengqikj.top/Article/details/gtodxrbxwl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.9152youxi.cn/Article/details/gtyyukfknu.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gtnplnjwai.html

Py:   str(42)
来源：http://dali.ydzc1.top/Article/details/gtrlxlxkvh.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuanzx.com/Article/details/gtyrwoyplr.html

JS:   String(42); (42).toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtladevfca.html

TS:   String(42)
来源：http://dali.iojbl.cn/Article/details/gtoohpjwai.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqayryykw.html

Go:   strconv.Itoa(42)
来源：http://dali.316326.xyz/Article/details/gtnfnjhtcb.html

Ruby: 42.to_s
来源：http://dali.chenzaomai.com/Article/details/gtiyaopdhp.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gtamlpydks.html

[A08] 取整与四舍五入
来源：http://dali.nanxinkj.top/Article/details/gtexbspteh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtchjkioog.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daria6918.cn/Article/details/gthbyakvxf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtcjyoqnka.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jianghu66.top/Article/details/gtwcwlmbfy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtsxiirclu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtfjjmattn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.9152youxi.cn/Article/details/gtmgaklhvj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtqiqhcqvz.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtinwdpuds.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gttkfnpcbk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtxartuknh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtdfogfkdm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtxzwwowpf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtgzlezbna.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tanke756.top/Article/details/gtnmgxxbfh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jiagoushi.top/Article/details/gtsqbdfzyc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtnfbgwqwo.html

[A10] 生成随机数
来源：http://dali.chenzaomai.com/Article/details/gtgvfkwsyn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hnqzz.top/Article/details/gtfcfjjutz.html

PHP:  random_int(1, 100);
来源：http://dali.shzxlz.cn/Article/details/gturcmsyxr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gtldwsjlbv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtifnlazts.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtyunjmhfn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cheryme.top/Article/details/gtskkquuhr.html

Ruby: rand(1..100)
来源：http://dali.gzhubu.top/Article/details/gtwuotwfpf.html

C#:   new Random().Next(1, 101)
来源：http://dali.nwbrower.top/Article/details/gtsblszrta.html

[A11] 条件表达式（三元）
来源：http://dali.quarkkingdee.top/Article/details/gtcgtbunph.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xziqi.cn/Article/details/gtqhcopqlo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtqngmvntx.html


<!-- 参考信息 -->