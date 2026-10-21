代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.guowangkeji.top/Article/details/gtwykweohx.html

composer require psr/container
来源：http://dali.tanke756.top/Article/details/gtftklxwwb.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gtnvpqbwpj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgufenzy.top/Article/details/gtukojbltu.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtbjsqvmkp.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gtqqgrlzxn.html

[U78] PHP：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbvxgwwn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gtthljxapl.html

[U79] PHP：静态分析
来源：http://dali.316326.xyz/Article/details/gtfmykxqto.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gtjwzdeksm.html

[U80] PHP：代码规范修复
来源：http://dali.shangyingyoupin.top/Article/details/gtqtelscju.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gtwofaxlql.html

[U81] JS：初始化项目
来源：http://dali.birdmap.top/Article/details/gtjczyzjfj.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gtuxitckow.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gtijypdwrt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtwgpsicdu.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtxpkytaat.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gtzimiotht.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtiieueytl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gthfnxujak.html

[U85] JS：可选链
来源：http://dali.gogol.net.cn/Article/details/gtwltcnphw.html

a?.b?.c
来源：http://dali.birdmap.top/Article/details/gtzbzjnxyl.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gtjhwqaxdf.html

a ?? b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkgtnxgr.html

[U87] JS：解构默认值
来源：http://dali.guannengcc.top/Article/details/gthjfifcdf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtcdrxwpfz.html

[U88] JS：对象展开合并
来源：http://dali.gotoacloud.top/Article/details/gtrftggczo.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gtnrkaveqb.html

[U89] JS：数组去重
来源：http://dali.cdnleiting.top/Article/details/gtmjqnlehe.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtqohkdite.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gtskjlaema.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtkgstmvrz.html

[U91] JS：对象键值遍历
来源：http://dali.yueranfly.top/Article/details/gtxhdfnbco.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gtsuiqonkv.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtgnxrkksg.html

structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbhjapkzl.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gtxxlgnddr.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gtmieddkye.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gtvppsuxff.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtknchryre.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gtlqaubyux.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gtmimiwojs.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gtntxqyccr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtsjodtmgj.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtrnjuqfcp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtgggpdipa.html

[U98] JS：fetch 带 JSON
来源：http://dali.gotoacloud.top/Article/details/gtqewmpswt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhengqikj.top/Article/details/gteskdejhm.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtruqebrbd.html

el.addEventListener("click", e => {})
来源：http://dali.quarkkingdee.top/Article/details/gtgtqjdbhj.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gtoiqohpln.html

document.querySelector(".item")
来源：http://dali.guannengcc.top/Article/details/gtlrfuzdyx.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gtzacnrefb.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gtfghshvnr.html

[U102] JS：本地存储
来源：http://dali.shzxlz.cn/Article/details/gtyybxuigx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gtyofycfge.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gtsjiuhfjz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.bjfxy.top/Article/details/gtxpjeixzd.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtobmpzubo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtmubbvcmu.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gtaeqenoou.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gtpdetrrae.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gtdjfsgfwh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gtscvonwry.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtaybajgmk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtbgfoahwc.html

[U108] JS：随机整数
来源：http://dali.jiagoushi.top/Article/details/gtaogfcovr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtpelduvlj.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gtrxqmxmjr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtimgoaznh.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gtjxsxsbrf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gththyjalz.html

[U111] JS：对象转 Map
来源：http://dali.shzxlz.cn/Article/details/gtrmchrrof.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gttmpqkqpq.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gtmibahgbw.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtmgzngkyz.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtssahsmad.html

s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtofljhojn.html

[U114] JS：JSON 深比较
来源：http://dali.wangshuangyany.cn/Article/details/gtshhyqhoj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtzrohnwzl.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtkyepnppw.html

crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtbpksudmx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gtduvbruky.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hysaishi.cn/Article/details/gtwxfldchy.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtlkabbflr.html

npm i -D vitest;  npx vitest
来源：http://dali.shuidangran.top/Article/details/gtgzgwzfil.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtwehoijdb.html

npm i -D vite;  npx vite
来源：http://dali.daxiang520.top/Article/details/gtahhwwita.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gtehantxym.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gtffrlpjrt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aizwys.cn/Article/details/gtufctivdn.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gtfvxusepm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtoktltbwf.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gttjrqkqdf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfiimaqbb.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtlowgouwg.html

Python ......... 252
来源：http://dali.0kj1m.cn/Article/details/gtzkopkwhp.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtrjsbawgf.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gtwziavget.html

TypeScript ..... 212
来源：http://dali.jinqigfzy.top/Article/details/gtfxpmreem.html

Java ........... 212
来源：http://dali.sweek.top/Article/details/gtblunpdov.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gtcjcvydvg.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtdsqxcuhs.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtkihhcter.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtctndmrhg.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gttamzcjpq.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gtcmfmwiip.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gthmpgyfpy.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtggxwaeaz.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtzxacgzwm.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gtksrczzbj.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gtwswqbgmk.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gtgitialhy.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtjtlpoubb.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gtzezccjty.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gtydpdvfrw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrhuqxof.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtlsbiewua.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtesqubmek.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtvhlzdlqh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtsdsauiye.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gtkttxvqkx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtzhxvffqj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gteblfcicf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gteyogzsfy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gttyfijrkd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtvzczomgg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtrczbnjqs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtbrmgtzrt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtqwlerqoo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ppjwa.cn/Article/details/gteyrcjwhe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuuvhnyq.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gttwduokhy.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gtvlpgccla.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gtvevibgso.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gtroryiock.html

U 高频实用片段                         120
来源：http://dali.yonumen.top/Article/details/gtkkzcwgeh.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtxpidxscn.html

合计                                  2106 条
来源：http://dali.tianlin.xyz/Article/details/gtucsynctn.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtciadcpqf.html

使用提醒
来源：http://dali.jiagoushi.top/Article/details/gttrmldcar.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gttydohend.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtxwslmtxj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtwkbvmylj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gtohhdqxaz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gtlxxhvzme.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cheryme.top/Article/details/gthwynvyen.html

—— 文件结束 ——
来源：http://dali.jinqigufen.top/Article/details/gtznjnotqk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthfpfqscg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gtgyqqcjhs.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gtpblpelhp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcrltgyvi.html

【收录内容】
来源：http://dali.chenjidiqi.icu/Article/details/gtvvzbqyes.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gtnmgcxamc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tianlin.xyz/Article/details/gtrkiiakaw.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gttznmpmis.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gtbfacpqbt.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gtunbmdybg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shzxlz.cn/Article/details/gtxwcmkcsg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxiorcqh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtnyrslevj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shangyingyoupin.top/Article/details/gtrzqsnvon.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gtlponbjsp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hongshengwenyu.top/Article/details/gtjonxldec.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gtrrwmhizv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuanzx.com/Article/details/gtnxukgypq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gtbtannucj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gtoollnhep.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.quarkkingdee.top/Article/details/gtwxrpjotn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sufxvd.cn/Article/details/gtpxrusfni.html

【文件统计】
来源：http://dali.dashuyun.cn/Article/details/gtxumjdgtv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtfqwxpnsh.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtjjpvdlpz.html

目  录
来源：http://dali.snrcjt.cn/Article/details/gtdgqcgsux.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtdiezohra.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtjttelgoc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtbeivoaos.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtubatgnyk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtisabqhci.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtktgwkxvq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtjrbogqul.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtpertyrdv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtwdnpdnkw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtiijuxhto.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyglakaqu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtcjkuunzx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtaasolsbs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtwzowfoum.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqjlvqjb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhengqikj.top/Article/details/gtanssjdgm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtximsidjd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ivvv.top/Article/details/gtboptwqjt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtjdohafcq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.316326.xyz/Article/details/gtshehpbxa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtsrobtiwj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gtibalmekv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfgljazup.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gtdlitpfbc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgdvedqad.html

[A01] Hello World
来源：http://dali.cucudq.cn/Article/details/gtgzdncwkh.html

Py:   print("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gttzloauot.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gtmdpfclkx.html

JS:   console.log("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtyesvcobf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gogol.net.cn/Article/details/gtwdhixfic.html

Java: System.out.println("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gttxkczttz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtrmthnwcb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhongyouzk.top/Article/details/gtxazkfnsb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtbfjbbgjt.html

[A02] 变量声明与赋值
来源：http://dali.ehwqpu.com/Article/details/gtgvkxzumc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jyoumei.cn/Article/details/gtonlipjgj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtyrogqsug.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yvedp.cn/Article/details/gteshwysqj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtaoxlpsod.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatvxubue.html

Go:   name := "Alex"; age := 20
来源：http://dali.ppjwa.cn/Article/details/gtplloabms.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gttquybses.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtlqceggom.html

[A03] 常量定义
来源：http://dali.zycfv.cn/Article/details/gtkxqwkrfv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dianchejie.cn/Article/details/gtbwndojxu.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtbrexfwfd.html

JS:   const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtvblzymvd.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjybjniey.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtteeexztg.html

Go:   const PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gtznaonstk.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gthqnipcci.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtfvbdzodu.html

[A04] 判断变量类型
来源：http://dali.tianlin.xyz/Article/details/gtrtsumnmt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ybcxt.top/Article/details/gtloedpfxc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.iojbl.cn/Article/details/gtuocmtjbn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gtarwqfhbp.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtnkvfdhxf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gtqufxsgvf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuanzhike.top/Article/details/gterbfafeq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugxaqpfj.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhcdozcf.html

[A05] 整数除法与取模
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjmyswjv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gthadmndft.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvppbmfg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtlnsbtehc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtzatetemy.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtrrmcjckv.html

Go:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtgbawdvvh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gteofvheju.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtlhhwcdao.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtyueuhwmm.html

Py:   int("42"); float("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtdrkpvnht.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhengqikj.top/Article/details/gtywcbgshh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gtpolokett.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daria6918.cn/Article/details/gtksmxuedl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtzfufjhzq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigfzy.top/Article/details/gtxtfkzkbx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gtcnhsqjtk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.meibo888.top/Article/details/gtvwzdxmdu.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtizdzqynz.html

Py:   str(42)
来源：http://dali.yanxiufei.cn/Article/details/gtlkysxnel.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnqzz.top/Article/details/gtogwpervl.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtsfveraxl.html

TS:   String(42)
来源：http://dali.9152youxi.cn/Article/details/gtyyfrrsjp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.quarkkingdee.top/Article/details/gtbpcoilms.html

Go:   strconv.Itoa(42)
来源：http://dali.nwbrower.top/Article/details/gtxjargjnf.html

Ruby: 42.to_s
来源：http://dali.jiagoushi.top/Article/details/gthtjglptz.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gtrofmxyfv.html

[A08] 取整与四舍五入
来源：http://dali.tanke756.top/Article/details/gtsfvrmedr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtxjssoqzh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj202588.top/Article/details/gtsbkjmqen.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtdnubszbm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gttbpsgdob.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtdrzgbocl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtgrsnayfa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gtwxhprjty.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtfcpadxaj.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gtubgydqkj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gtxjqocwfg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfqcoccc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsbxnuad.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkhevxgkt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtyptyxrog.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cucudq.cn/Article/details/gtbtihdjte.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gogol.net.cn/Article/details/gtqecunxqg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtuhsdwyiy.html

[A10] 生成随机数
来源：http://dali.hnxiangtu.top/Article/details/gtrhphrjpq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jyoumei.cn/Article/details/gtzkivuals.html

PHP:  random_int(1, 100);
来源：http://dali.mhx1999.top/Article/details/gthisffshr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtwuuhyzih.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtdzpymkxp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj202588.top/Article/details/gthhdaeozt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daria6918.cn/Article/details/gtpxomzuwu.html

Ruby: rand(1..100)
来源：http://dali.zhiwuduotai.top/Article/details/gtuvuarxuk.html

C#:   new Random().Next(1, 101)
来源：http://dali.haohaochexian.top/Article/details/gtoybunlyl.html

[A11] 条件表达式（三元）
来源：http://dali.ydzc1.top/Article/details/gtviiofaad.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ppjwa.cn/Article/details/gtdxjhyrkl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtpywteuau.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtrlslizac.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtndypsyee.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtcydwptax.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgufenzy.top/Article/details/gtmoivvmlw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gttixpsgtf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtatumjvsc.html

[A12] 字符串插值 / 格式化
来源：http://dali.fzhhl.top/Article/details/gtgglafijc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuxming.cn/Article/details/gtehhpraej.html


<!-- 参考信息 -->