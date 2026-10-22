代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gtvnmgviym.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gtptezyhre.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gtnninkfmx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtinbelhod.html

[U77] PHP：模板渲染
来源：http://dali.hammf.cn/Article/details/gtnaayxnhd.html

composer require twig/twig
来源：http://dali.zhixingplan.top/Article/details/gtqvdgymqb.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtchxrdanj.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gtzildbsvn.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gtqamuckkg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtrskhuwrj.html

[U80] PHP：代码规范修复
来源：http://dali.nanxuanxn.top/Article/details/gtrvlimlvi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gtaikmpsmh.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufldxskj.html

npm init -y;  npm i express
来源：http://dali.ehwqpu.com/Article/details/gthklstuyh.html

[U82] JS：package.json 脚本
来源：http://dali.bjfxy.top/Article/details/gtagyvpkai.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhoulong.xyz/Article/details/gtfcklwkhk.html

[U83] JS：ES Module 导入导出
来源：http://dali.shuidangran.top/Article/details/gtcfqaacrl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtmaodpgxi.html

[U84] JS：CommonJS 写法
来源：http://dali.sysykeji.top/Article/details/gtvtszyqmk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.c1oappe.top/Article/details/gtzbxvablb.html

[U85] JS：可选链
来源：http://dali.zhongyouzk.top/Article/details/gtmrnhfczi.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gtyhjlcdqq.html

[U86] JS：空值合并
来源：http://dali.yj20258.top/Article/details/gtwaetqscm.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gtrfaexekd.html

[U87] JS：解构默认值
来源：http://dali.guannengcc.top/Article/details/gtklhakxwc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtwdfyiuij.html

[U88] JS：对象展开合并
来源：http://dali.0kj1m.cn/Article/details/gtpqielogy.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gtlvzexvld.html

[U89] JS：数组去重
来源：http://dali.sysykeji.top/Article/details/gtmjjhtvuq.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtmjpljmmv.html

[U90] JS：数字数组排序
来源：http://dali.jinqigufen.top/Article/details/gtqifyfrph.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtctyyuaid.html

[U91] JS：对象键值遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtozokwosu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigufen.top/Article/details/gtbshfdjhk.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtfcoucbqd.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtutirfbtq.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtakngcwsa.html

`共 ${n} 条`
来源：http://dali.bjfxy.top/Article/details/gtsqzpwikg.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtesythudy.html

const double = x => x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gtdvszeoiq.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gtlsccjcjr.html

new Promise((resolve, reject) => {})
来源：http://dali.yanxiufei.cn/Article/details/gtzvwjlaxn.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeafmwhc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtpqlqiviu.html

[U97] JS：并发请求
来源：http://dali.cqqwz.cn/Article/details/gtlazkztkr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gttonqzmpx.html

[U98] JS：fetch 带 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtvkifgucs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gtnhxrtmeg.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gtqzkypgvw.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gtktdhwemk.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gthmqhmqzq.html

document.querySelector(".item")
来源：http://dali.0kj1m.cn/Article/details/gtnxnotufa.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gtsmkwzzfl.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtfmlfpcva.html

[U102] JS：本地存储
来源：http://dali.jlsjyb.cn/Article/details/gtbcnlfmmk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gtcpfrpgen.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gtxlspcrmu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtabkhosco.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gtpurwbgfz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtiwhyiqmy.html

[U105] JS：节流
来源：http://dali.0kj1m.cn/Article/details/gtikcludzn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtyygpzpwj.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gttcttmywc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gtjfsbqsuq.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtkqhaueab.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gtiwpacgbp.html

[U108] JS：随机整数
来源：http://dali.c1oappe.top/Article/details/gtqjhuzbum.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gtjtqbovba.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gtdwvnlcmr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtsyrxugob.html

[U110] JS：数组分块
来源：http://dali.yonumen.top/Article/details/gtpnjogmzu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gtyobdpioq.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtskhqywdy.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gttphhhjfy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gtlpnywszj.html

"7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtagzegquw.html

[U113] JS：正则替换全部
来源：http://dali.sxryk.cn/Article/details/gtfokqeljl.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtgwrntxul.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gtopiaawpu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgstihpq.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtpekjtttq.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtunhrhtjn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gtchkuukma.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sxryk.cn/Article/details/gtamiaymcb.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtaokmyfuq.html

npm i -D vitest;  npx vitest
来源：http://dali.yvedp.cn/Article/details/gtrrtyhhyd.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gtgbuwjunf.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gtvzfowuye.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gthzyhcxvg.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtsintdyrf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gtyhiwqyui.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gtvurcywfq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaulbbfop.html

统计汇总
来源：http://dali.svipenyu.cn/Article/details/gtqopchvxs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrkjzzlsu.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gtazmbiqgp.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gtznfslkke.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gttdwajgee.html

JavaScript ..... 252
来源：http://dali.chenlongwang.top/Article/details/gtrrqpfdfu.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gtoqbrloii.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtcoigkkva.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gtrgwtejcn.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtinmgdfsl.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtsmwjhvus.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gthmhgrhyi.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtvufayrzh.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtvgblpxvw.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gtdzzvahzq.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gtukfnjfcn.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofbcyomw.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtbcwhgtwz.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gtlfasmfps.html

Scala .......... 10
来源：http://dali.gaohongyu789.top/Article/details/gthfwtwxia.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtwgxnjjiw.html

合计 ........... 2106 条
来源：http://dali.svipenyu.cn/Article/details/gtxartcgoe.html

按章节统计：
来源：http://dali.nanxuanxn.top/Article/details/gtlzzeuzvg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvthrhrre.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtbwjkjzsd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtioeaamrv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtusuuonpr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dashuyun.cn/Article/details/gtvrrhzsua.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtdbdbcitx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtpudmiein.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtvocmmtyq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtzmiaohmi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtcqswttzc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtmpwjkirz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtpkgllmje.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtdlzwinev.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtrbllxjec.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gtfcvjthsf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gteulaqksk.html

Q SQL 专题                              90
来源：http://dali.zhoulong.xyz/Article/details/gtxwtctwmq.html

R Bash 专题                             80
来源：http://dali.kuanghao11.cn/Article/details/gtzindnwqh.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gtzrzjslzh.html

T 其他语言补充                          60
来源：http://dali.cdnleiting.top/Article/details/gtgktwiofy.html

U 高频实用片段                         120
来源：http://dali.ivvv.top/Article/details/gtculmsoii.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtbpxzszcg.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtaimwddop.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtzrqiiilk.html

使用提醒
来源：http://dali.hfpthk.cn/Article/details/gteocxdcme.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtyuioyyak.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gtigywpars.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sysykeji.top/Article/details/gtrthgrmmv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gtxsxiysmd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnqzz.top/Article/details/gtxzynigpl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gtzafekwqr.html

—— 文件结束 ——
来源：http://dali.cqqwz.cn/Article/details/gtaxlqdade.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtyopqqi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.c1oappe.top/Article/details/gthwkwgvkz.html

Common Programming Examples Cheat Book
来源：http://dali.hammf.cn/Article/details/gtnmxysvqf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgbsjcrop.html

【收录内容】
来源：http://dali.chenjidiqi.icu/Article/details/gtsjmltfwr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtngjxtaqr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gtphipcugb.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gtogjjguen.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.kuanghao11.cn/Article/details/gtpnkspwnn.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gtxmtsyxwf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gtcsssejdk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zycfv.cn/Article/details/gtmrkapwem.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yanxiufei.cn/Article/details/gtvzpthrpz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yanxiufei.cn/Article/details/gtjuxegntf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gtlzbxhhic.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.meibo888.top/Article/details/gtzapdxnys.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guannengcc.top/Article/details/gtgmtrurmp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhixingplan.top/Article/details/gtsxgartys.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258.top/Article/details/gturnpyirl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gtbqghqlpj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gthahyfzkg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhengqikj.top/Article/details/gtocowtrfj.html

【文件统计】
来源：http://dali.chenzaomai.com/Article/details/gtbzvessck.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dashuyun.cn/Article/details/gthxuqalut.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtocuhqdft.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtceqwwmnj.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtxxpdflrz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtfmtirqss.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtcwjfsqlv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtjulkyzot.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gthaycbrak.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jiagoushi.top/Article/details/gtpjylgiwz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzwltxov.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtpkuphbkv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtiaipiapl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtfgemgrzn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtzvjgtkvx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gttuimepbq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtdqlcarff.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtyiuxaaga.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtsvsvqccr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fzhhl.top/Article/details/gtqkhmzyyr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtjrtfolld.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gtkeljdpvi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xylfe.cn/Article/details/gtzzafhwrv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtanmxncyd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gticadpnyc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpznvbag.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlgszgskc.html

A. 基础语法与类型
来源：http://dali.dianchejie.cn/Article/details/gtsnwkosmq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsdbqnqtj.html

[A01] Hello World
来源：http://dali.jiagoushi.top/Article/details/gtxhqzlnnb.html

Py:   print("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtchgoewns.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258.top/Article/details/gtbljofugd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtsukvxlmp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gtwtvvowos.html

Java: System.out.println("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtdjogfwjq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtfpffpjpy.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigufen.top/Article/details/gteiohcgwx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtfwyqqnvl.html

[A02] 变量声明与赋值
来源：http://dali.wangdashe.top/Article/details/gtxfxgxxst.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgfzy.top/Article/details/gtrrdyhltj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtrpsosbmw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtisindlfk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tian-w.cn/Article/details/gtwqwvzjms.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtynwhzukw.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gtxofpvzuc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gtiynkvowu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtomuhxwfj.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gtjlqmyghe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.c1oappe.top/Article/details/gtpfpoclhi.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtksjqilch.html

JS:   const PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtsepgkbjo.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtkycvlzkn.html

Java: static final double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtewreixvt.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtgxkinnuw.html

Ruby: PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtmhgqkzzy.html

C#:   const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtbjyssdhg.html

[A04] 判断变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtswevhqzi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258.top/Article/details/gtdqrlorct.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpoxylxp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gtxonvhcxz.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtnjwfrmnh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.vqdsnc.cn/Article/details/gtsjnboenq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj202588.top/Article/details/gtkjhxemdd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhengqikj.top/Article/details/gtwjhfzqfv.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuetiantiany.cn/Article/details/gtlegpkmmm.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gtczxmthey.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hammf.cn/Article/details/gtkbktovrm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzbioojp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtutorifks.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtreywcmql.html

Java: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtwqgkxuoy.html

Go:   7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtegyqwipg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtipwjqafn.html

C#:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtghyuossc.html

[A06] 字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtqublkxro.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtiwmdtfwo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ivvv.top/Article/details/gtucbysien.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtzvexlkrz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sysykeji.top/Article/details/gtdkblhnuz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuxming.cn/Article/details/gtvivcepcz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shuidangran.top/Article/details/gtqrctudts.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aizwys.cn/Article/details/gtsqgaeaxb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ivvv.top/Article/details/gtvssmbpny.html

[A07] 数字转字符串
来源：http://dali.yangfankeji.com/Article/details/gtbdizxmbp.html

Py:   str(42)
来源：http://dali.yj20258.top/Article/details/gtsgkedcag.html

PHP:  (string) 42; strval(42)
来源：http://dali.sxryk.cn/Article/details/gtuogiwetr.html

JS:   String(42); (42).toString()
来源：http://dali.yongpay.top/Article/details/gthgkgsfyh.html

TS:   String(42)
来源：http://dali.wangdashe.top/Article/details/gtexckyzbb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxuanxn.top/Article/details/gtamcimckr.html

Go:   strconv.Itoa(42)
来源：http://dali.vqdsnc.cn/Article/details/gttvnreptl.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gtvkpfteyz.html

C#:   42.ToString()
来源：http://dali.fengsongda.top/Article/details/gtbpxvhwrp.html

[A08] 取整与四舍五入
来源：http://dali.yuxming.cn/Article/details/gtdfpbkzgn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gthpbthkij.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gogol.net.cn/Article/details/gtqhvxhplj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gthgixyrpd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangshuangyany.cn/Article/details/gtlaftpuyu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtgazsxgat.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtioqjvwnk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jianghu66.top/Article/details/gtxlxdjeuf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqspfhxf.html

[A09] 绝对值与最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtmahghdbh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtpqcdwqrn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtlseckmcn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtppwafvls.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtdvkqzpcw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnsctvanp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuljucql.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gthmvhoogr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtzumjlrqn.html

[A10] 生成随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtduyxdpnl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenjidiqi.icu/Article/details/gtbaykmsct.html

PHP:  random_int(1, 100);
来源：http://dali.shangyingyoupin.top/Article/details/gtfdxjefjs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtyklbtwwh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtnpxzmthg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtbonvrbtq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gtudvdargj.html

Ruby: rand(1..100)
来源：http://dali.hfpthk.cn/Article/details/gtjgnwzcmp.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gtsqskudql.html

[A11] 条件表达式（三元）
来源：http://dali.gaohongyu789.top/Article/details/gtmtsvqtbv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.fengsongda.top/Article/details/gtkxizdyzb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtrgchvjsn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtppipzcmv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtvcyxluvz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtvndhrmhb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sxryk.cn/Article/details/gtuchbgpsb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsutzoqfh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtxdpwmgty.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenjidiqi.icu/Article/details/gteordttyr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cheryme.top/Article/details/gtqdzvvdct.html


<!-- 参考信息 -->