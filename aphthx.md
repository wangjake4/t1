代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.snrcjt.cn/Article/details/gtjquelbsm.html

parse_ini_file("config.ini", true)
来源：http://dali.hysaishi.cn/Article/details/gtevhqzqhk.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtlormgnkd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsqxrtze.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gtdafzpwuc.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gtlprjzhct.html

[U76] PHP：简单路由
来源：http://dali.gzhubu.top/Article/details/gtvdqjupta.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jianghu66.top/Article/details/gtnnmtiknh.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangtech.top/Article/details/gtflqrqcix.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gtuguaeqrp.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtzrkohiah.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gtenientna.html

[U79] PHP：静态分析
来源：http://dali.vqdsnc.cn/Article/details/gtjcdawzdo.html

composer require --dev phpstan/phpstan
来源：http://dali.gaohongyu789.top/Article/details/gtvkpmqmdf.html

[U80] PHP：代码规范修复
来源：http://dali.sufxvd.cn/Article/details/gtabjfrrms.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtcqpauqhq.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gtsmfdjxid.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtzsiuadew.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gtuubyxrqr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gtwsgwlrbo.html

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gtliupjwre.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gttoisqirk.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gtvuajxawp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gtgwdrvqdj.html

[U85] JS：可选链
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhnzwptx.html

a?.b?.c
来源：http://dali.chenlongwang.top/Article/details/gtglckwuew.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkznxrla.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gtectzeqgt.html

[U87] JS：解构默认值
来源：http://dali.dashuyun.cn/Article/details/gtkujtsagm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gtgjozwiwp.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvawxqivw.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gtsbmenqct.html

[U89] JS：数组去重
来源：http://dali.nanxinkj.top/Article/details/gtnwzhotxa.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtpunqayrf.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gtcpnxjywz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtuyjspzve.html

[U91] JS：对象键值遍历
来源：http://dali.zhengqikj.top/Article/details/gtnljdbads.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigfzy.top/Article/details/gtcwdnrivi.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtwhwyhvml.html

structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtnlmnvhtp.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkactroq.html

`共 ${n} 条`
来源：http://dali.meibo888.top/Article/details/gtkrubezsk.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gtruhsurpd.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtiyxlkcxy.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gtypkeirww.html

new Promise((resolve, reject) => {})
来源：http://dali.sxryk.cn/Article/details/gtukbrtpoc.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gtrmzdwema.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gthvbsoyqu.html

[U97] JS：并发请求
来源：http://dali.ehwqpu.com/Article/details/gtsycmmiex.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtuconuila.html

[U98] JS：fetch 带 JSON
来源：http://dali.zycfv.cn/Article/details/gtgyqzwmbu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fzhhl.top/Article/details/gtyptrtmdv.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gtgcedkvsi.html

el.addEventListener("click", e => {})
来源：http://dali.ybcxt.top/Article/details/gtsoxiohzl.html

[U100] JS：DOM 查询
来源：http://dali.c1oappe.top/Article/details/gtwuvpejgp.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtinpgnval.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gtoujscfip.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gtjadndkic.html

[U102] JS：本地存储
来源：http://dali.mhx1999.top/Article/details/gtqbpwdjcc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtmrbfhtxy.html

[U103] JS：定时器
来源：http://dali.quarkkingdee.top/Article/details/gtjqtsscuv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtolichgqu.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtxchqavye.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtwpbgsgug.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gtheorbjcu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gtapjsqfhj.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbgnlixk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gturbatdxm.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gtwvjnbknx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ivvv.top/Article/details/gthndrytge.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtiqojgngi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.svipenyu.cn/Article/details/gtmpsidosp.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gtxqcvoyla.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtydqbyuan.html

[U110] JS：数组分块
来源：http://dali.aizwys.cn/Article/details/gtbnhwsnum.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gtzmoyygrl.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtsnajzrvo.html

new Map(Object.entries(obj))
来源：http://dali.shuidangran.top/Article/details/gtdwzhxgzg.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gtuvupndwy.html

"7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtqrfolueg.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtbctjfrdd.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtvgzzgbbt.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gtdzgoqzzh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtvsliptnx.html

[U115] JS：生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtstsguzde.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtmgdvuftn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gtzrgjbpij.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gtybpnsifl.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtsofsptma.html

npm i -D vitest;  npx vitest
来源：http://dali.c1oappe.top/Article/details/gtxakyxkls.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gtdddubrng.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gtyojyhlwn.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosjbrrqz.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtjddxlvxb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gtygxlnhwq.html

import.meta.env.VITE_API_URL
来源：http://dali.hywenlv.cn/Article/details/gtcdurhbty.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtafzijolt.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gtszxjnnhv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpylkdycw.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gtoezvbgph.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gtwcihjous.html

PHP ............ 252
来源：http://dali.xuetiantiany.cn/Article/details/gtdbejzbfx.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gtzyaaxwfv.html

TypeScript ..... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsifxobx.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtkspubsdb.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtyykpcttl.html

Ruby ........... 212
来源：http://dali.bjfxy.top/Article/details/gtdgwyoyuf.html

C# ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtaadvbzwj.html

C .............. 30
来源：http://dali.jyoumei.cn/Article/details/gtitxlaxzy.html

C++ ............ 30
来源：http://dali.hywenlv.cn/Article/details/gtujtsslhs.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gtnxqralmt.html

Bash ........... 80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhdvyuie.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtxrmrwusm.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtuvybeiiw.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gtudnxjklp.html

Perl ........... 10
来源：http://dali.dashuyun.cn/Article/details/gtydolyefo.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gtprnbfbkc.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtlenuweax.html

合计 ........... 2106 条
来源：http://dali.9152youxi.cn/Article/details/gtwywwgcgy.html

按章节统计：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnasxhkfi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtwhkawaup.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtmsudnewp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtsxwwlvdl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtfishywtl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gtxleghgon.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtnxelznkq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtlyjnsccx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtdqyevsam.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtuxgyvige.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtxgjduuzr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtgdhguxek.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtjeywtbfo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtnounaxki.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtzhwtwdre.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gtsyfulibm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtibipjtdl.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gtojzmceba.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gtyutkjbqt.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gtpdgtrpbk.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtbualyozg.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gtfurlahdd.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtbnteevbs.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gtngaegtzn.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtuqereewx.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzpbngoz.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtpzsrpyzt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gtzomhxiai.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dashuyun.cn/Article/details/gthuiepuxo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.0kj1m.cn/Article/details/gtejhdewxf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yanxiufei.cn/Article/details/gtaeosdlrl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gtvysdxjim.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gtxnbfyzdy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcnppxvmy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ppjwa.cn/Article/details/gtbhrbbmzd.html

Common Programming Examples Cheat Book
来源：http://dali.xylfe.cn/Article/details/gtbrxuqlaw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxtzmmrjn.html

【收录内容】
来源：http://dali.hfpthk.cn/Article/details/gtwdgihxqa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinghuilouyu.cn/Article/details/gtaezmckab.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gtunkjfibg.html

SQL · Bash · C · C++
来源：http://dali.ivvv.top/Article/details/gtqkzujdso.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.9152youxi.cn/Article/details/gtrlvkchcb.html

【使用说明】
来源：http://dali.mhx1999.top/Article/details/gtozfscxhm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gtrrrurhea.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.haohaochexian.top/Article/details/gtjlnvkaem.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hongshengwenyu.top/Article/details/gtureangvm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.mhx1999.top/Article/details/gtgzprbzfm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zdqjudy.top/Article/details/gtgyslehwy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gtlyzjmddn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.svipenyu.cn/Article/details/gtxbgislng.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.feifeiyinyue.top/Article/details/gtivpjwtgz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gtghfwtbck.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpqofmzg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jianghu66.top/Article/details/gtueeoguph.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gogol.net.cn/Article/details/gthmjrnnfj.html

【文件统计】
来源：http://dali.chenjidiqi.icu/Article/details/gtjstswdll.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gtzfwupkyf.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtvgwfilwq.html

目  录
来源：http://dali.jinqigufen.top/Article/details/gttjkhmdnu.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtqxuhixss.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtlnxquqee.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtchzarljy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtcrwilhal.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalmwbimv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhixingplan.top/Article/details/gtpacogaxs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtnnjbozqq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtcquuuxvu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtimunrnnt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtvqetfqxh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtnuufsvtw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtjwmacahe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtjsxfpnsz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoizronh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtnwputqcv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.pycfn.com/Article/details/gttpomflxp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtrhzksgqp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shuidangran.top/Article/details/gtgtpgrlfd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tian-w.cn/Article/details/gtukomvyie.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.svipenyu.cn/Article/details/gtwwxqcbfc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtyymymupj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtxrqgrdow.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagqbtynf.html

A. 基础语法与类型
来源：http://dali.fengsongda.top/Article/details/gtzlqbimvr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzwovteav.html

[A01] Hello World
来源：http://dali.zhoulong.xyz/Article/details/gteqslpbha.html

Py:   print("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gtotsiatmo.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gtkrqwvzkn.html

JS:   console.log("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gtazzzeybl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gtkqfwxjwo.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtvnqpvsrr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yongpay.top/Article/details/gtoqawhjwn.html

Ruby: puts "Hello, World!"
来源：http://dali.sxryk.cn/Article/details/gtloegpbia.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtwzlaeyzw.html

[A02] 变量声明与赋值
来源：http://dali.yonumen.top/Article/details/gtdcskdewc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yongpay.top/Article/details/gtptekaxsk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtkeiqfkya.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtycufqkmi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sufxvd.cn/Article/details/gtsrssgthb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gtabsgcnzj.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtnqlmrsvn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenjidiqi.icu/Article/details/gtlpuzlfpg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtnowevnyl.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gtcmyplmij.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ehwqpu.com/Article/details/gtgszugiio.html

PHP:  const PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gttzzeqlvh.html

JS:   const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtvipxuzhx.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtnrcvudah.html

Java: static final double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtzkzhagcf.html

Go:   const PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtlgcybsee.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtsukodtqj.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtmnfvdlqm.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gtplwbppph.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aizwys.cn/Article/details/gthmdjfbxj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxinkj.top/Article/details/gttefrcant.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmavxwyn.html

TS:   typeof x; x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gtlpafbaop.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgfzy.top/Article/details/gtvjztpbhc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fengsongda.top/Article/details/gtollpfiyt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yonumen.top/Article/details/gtuwbyzmsd.html

C#:   x.GetType().Name; x is int
来源：http://dali.gzhubu.top/Article/details/gthfythwna.html

[A05] 整数除法与取模
来源：http://dali.zdqjudy.top/Article/details/gtzuzelsru.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gtcbafjgau.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtqqnplooj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtwpevwbuv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtfgcbrocg.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxjzntvf.html

Go:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtxksxymhv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtfekahqvd.html

C#:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtksbkrlbh.html

[A06] 字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtivjsuxcp.html

Py:   int("42"); float("3.14")
来源：http://dali.cdnleiting.top/Article/details/gtmomsuhnr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cqqwz.cn/Article/details/gtyvfqwumx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtfayajbkw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ivvv.top/Article/details/gtgfedzkub.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtxgsowamt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gtxuppnnfg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gtoefvezmk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgohtmnd.html

[A07] 数字转字符串
来源：http://dali.yangfankeji.com/Article/details/gtcmxrmizz.html

Py:   str(42)
来源：http://dali.yueranfly.top/Article/details/gtbvkjuusj.html

PHP:  (string) 42; strval(42)
来源：http://dali.andypj.xyz/Article/details/gtvubbmfki.html

JS:   String(42); (42).toString()
来源：http://dali.jyoumei.cn/Article/details/gtxxlhjkdd.html

TS:   String(42)
来源：http://dali.sxryk.cn/Article/details/gtcbtryeqh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jlsjyb.cn/Article/details/gtkzdertwm.html

Go:   strconv.Itoa(42)
来源：http://dali.vqdsnc.cn/Article/details/gtqwbaivxv.html

Ruby: 42.to_s
来源：http://dali.sweek.top/Article/details/gtvursjbma.html

C#:   42.ToString()
来源：http://dali.sysykeji.top/Article/details/gthpbxhhkc.html

[A08] 取整与四舍五入
来源：http://dali.yangfankeji.com/Article/details/gtcegwhzyq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtpnhbrxuf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfepenntd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtiziqnswy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.9152youxi.cn/Article/details/gtfcetjhfu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtgkopbbba.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtnfmcmxzg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shanyushiyangtech.top/Article/details/gtoakeynhb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtztjhxoye.html

[A09] 绝对值与最大最小值
来源：http://dali.ydzc1.top/Article/details/gtxwkmfvzx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtfirvynaw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtnnnhkhtx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtowziwjaw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gtjxifgwnl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cashguo.top/Article/details/gtbkgbhtep.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj20258.top/Article/details/gtdantntqw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pengpengdd.cyou/Article/details/gtngaeskpb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtytysbyww.html

[A10] 生成随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtngboemlv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ppjwa.cn/Article/details/gtqobnjlhl.html

PHP:  random_int(1, 100);
来源：http://dali.yangfankeji.com/Article/details/gtkygyopii.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtgxxjrvvs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtnczlzvnu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtrplfjhrd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokhcbrri.html

Ruby: rand(1..100)
来源：http://dali.aizwys.cn/Article/details/gtmpscocbi.html

C#:   new Random().Next(1, 101)
来源：http://dali.0kj1m.cn/Article/details/gtcozwzsay.html

[A11] 条件表达式（三元）
来源：http://dali.cqqwz.cn/Article/details/gtxbkamyll.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigfzy.top/Article/details/gtyecawdac.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gttxpopwfa.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtpkxkpopv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtbrhtvlgh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtwueavmev.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ehwqpu.com/Article/details/gtszmsrgbx.html


<!-- 参考信息 -->