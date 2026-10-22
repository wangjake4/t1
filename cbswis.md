代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.zhixingplan.top/Article/details/gtygsnrsxu.html

parse_ini_file("config.ini", true)
来源：http://dali.kuanghao11.cn/Article/details/gtdhkcohdl.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gttwbftwas.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gtwfxuzseq.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gtrlwjebsl.html

composer require psr/container
来源：http://dali.cqqwz.cn/Article/details/gtxgltdytx.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtlnvvpudm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gthzazysle.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gtqqcpfoxh.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gtiijxfqgj.html

[U78] PHP：单元测试
来源：http://dali.smart0.xyz/Article/details/gttbirwhby.html

composer require --dev phpunit/phpunit
来源：http://dali.wangdashe.top/Article/details/gtankvwyyp.html

[U79] PHP：静态分析
来源：http://dali.hfpthk.cn/Article/details/gtnedahghb.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gtagurdbnk.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gtzppfrlxm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gtryjfxyrt.html

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gthyzswthv.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gtsfxqncjz.html

[U82] JS：package.json 脚本
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtsjoxol.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuanzhike.top/Article/details/gtnkfopfoq.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuanzx.com/Article/details/gtpdhbjian.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtzzhpurvn.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gtcztrxjdq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pycfn.com/Article/details/gthcejxlyh.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gtiokcmcmd.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gtruxzsakw.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtjcvgentv.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gtjsvqwurr.html

[U87] JS：解构默认值
来源：http://dali.guannengcc.top/Article/details/gtudjlgpse.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenlongwang.top/Article/details/gtqvbkrooj.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gtdryjqucy.html

{ ...a, ...b }
来源：http://dali.yanxiufei.cn/Article/details/gtrgyyeewt.html

[U89] JS：数组去重
来源：http://dali.chenlongwang.top/Article/details/gtbogzyezl.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtswlfokvp.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gtxarcnnnr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtgnalugjx.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtihmijpiz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gtcdyscipd.html

[U92] JS：深拷贝
来源：http://dali.daxiang520.top/Article/details/gtqhcrnnoo.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtfbhcvaco.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gtrgvczgoj.html

`共 ${n} 条`
来源：http://dali.yj20258.top/Article/details/gtlfqrpahu.html

[U94] JS：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtqqhmywfu.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtfjdswjax.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gtcxihtpcd.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gtpfyjrysn.html

[U96] JS：async/await 与异常
来源：http://dali.yangfankeji.com/Article/details/gtxevlzkum.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpoydaqfo.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtowqokcql.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtrvtigdgw.html

[U98] JS：fetch 带 JSON
来源：http://dali.haohaochexian.top/Article/details/gtmrfvyrih.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gtecxunord.html

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gtcelvewqz.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtvxcdbwnn.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gttwbuqmhq.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtmkheyinu.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtwuxaqljw.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gtxzyqwfzg.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtyscbhsnn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcdefxex.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gtpoanyinr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtcgulgiyn.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gtgoniktru.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtytlerzlr.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gtlbdklaar.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gtyzugviig.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtfbtuhenw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gtniplvrlt.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtuknygkfy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngvhogkl.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gtfvwysocf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenlongwang.top/Article/details/gtmaamjszk.html

[U109] JS：数组分组
来源：http://dali.zhengqikj.top/Article/details/gthwmpsmvz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtaqfqupxa.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gtjlrxvlhq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gtysgfswkv.html

[U111] JS：对象转 Map
来源：http://dali.cheryme.top/Article/details/gtiwyhhkrj.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gtzphlstwl.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gttarvekim.html

"7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfqpbmbf.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gtvknjycch.html

s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtggsypukq.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtvmwlbtvt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtslarbknl.html

[U115] JS：生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtngecpcdc.html

crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtwfvzwdvx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtkmksfbyg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gthzlnksaq.html

[U117] JS：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtkljngcpj.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoxyvygg.html

[U118] JS：开发服务器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolyxhcpc.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gtpycgbrof.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtbmiqsepn.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gtyujgzkwz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pengpengdd.cyou/Article/details/gtfsalzhyv.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gtasawgvnh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxtbiluo.html

统计汇总
来源：http://dali.shangyingyoupin.top/Article/details/gtgwnfnkum.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsaduwgpj.html

按语言统计（条）：
来源：http://dali.ppjwa.cn/Article/details/gtwflwfrkd.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gthryctegw.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtavmxpbzh.html

JavaScript ..... 252
来源：http://dali.zhiwuduotai.top/Article/details/gtzkqqprur.html

TypeScript ..... 212
来源：http://dali.sweek.top/Article/details/gtzpigbfhk.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gtusysgmyy.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgtqgkgo.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gtzvsnubql.html

C# ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtrrskbpve.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtpvptbuha.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gtstlauzsr.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gtommxuzvv.html

Bash ........... 80
来源：http://dali.yonumen.top/Article/details/gtzfntprgw.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtmkgyebyv.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtrogvpfde.html

Lua ............ 10
来源：http://dali.dashuyun.cn/Article/details/gtjznkjnsu.html

Perl ........... 10
来源：http://dali.tanke756.top/Article/details/gtwxtqyvzi.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gtymlggveq.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtqhuycclh.html

合计 ........... 2106 条
来源：http://dali.tian-w.cn/Article/details/gtcpnehqrv.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtkeahpmth.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gtrarmxcww.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gthcnmbjkm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtnvwbzhra.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtjjxvavuq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gtamafpdgj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gttoefvimh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtfwmmcmgj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtrbfhsupl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtdsnagsno.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtjarfycoz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtkrsrbomh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtvmkbhfuu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtocondwxj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtlsbeesaf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.mhx1999.top/Article/details/gtjgcwoylv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtiqhumpol.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gtsbkmqbhy.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gtkmrmxfzu.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdykaqej.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gtkbvuzqss.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gtzhcutlkj.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtwlehsqot.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gtvyjkoazm.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtmpktgbik.html

使用提醒
来源：http://dali.havefunace.top/Article/details/gtgovwrlcc.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtgajiuxew.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gtxjgipbsa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj202588.top/Article/details/gtxnwmndrf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aizwys.cn/Article/details/gtdpqkqiio.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gtxrpguruj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daria6918.cn/Article/details/gtitavoqxf.html

—— 文件结束 ——
来源：http://dali.shuidangran.top/Article/details/gtmifuouzt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdaujukkb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigfzy.top/Article/details/gtmgydotfu.html

Common Programming Examples Cheat Book
来源：http://dali.jianghu66.top/Article/details/gtdfdpukat.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkplzvmfq.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gtpygoibbf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxinkj.top/Article/details/gtjcvvmqnj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgfzy.top/Article/details/gtmrajzdxt.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gtuvtczttz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pengpengdd.cyou/Article/details/gtdjknlfrz.html

【使用说明】
来源：http://dali.quarkkingdee.top/Article/details/gtnmahtcnr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zdqjudy.top/Article/details/gttdjefkpy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jlsjyb.cn/Article/details/gtnqzercvb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhiwuduotai.top/Article/details/gtnuvongea.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkcaftqs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gtonumzsqu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gtnefnuhmg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gtvuwdkiue.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhoulong.xyz/Article/details/gtmnlicwzk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkplmhapp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gteuexzhix.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.vqdsnc.cn/Article/details/gtnlktarzq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zycfv.cn/Article/details/gtadsegbda.html

【文件统计】
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxaavcaa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yanxiufei.cn/Article/details/gtgzoegwos.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtognffsyg.html

目  录
来源：http://dali.chenzaomai.com/Article/details/gtywuuhlnx.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtuwhlsgpp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sweek.top/Article/details/gtgtesbnyn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtwtyhbvtt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtaossxqqw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtzsrxvgxk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtfxnmmndk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtfpucrhni.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtgjdcdslg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtirlasric.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtdkpxazei.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gtnujhtdci.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtuoxibzxe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtupucxohm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtxwlcesvv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtycktpkci.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ppjwa.cn/Article/details/gtrdkhdqqu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtevwsqhmk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtiellkrmq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtogkthbnr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guowangkeji.top/Article/details/gtaxoiqbzm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtbwtixtka.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gtekfjcvbm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttrmkhxfs.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gtfcfxrzpx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsufznwll.html

[A01] Hello World
来源：http://dali.ydzc1.top/Article/details/gtlnufzdux.html

Py:   print("Hello, World!")
来源：http://dali.wangdashe.top/Article/details/gtuywwpktb.html

PHP:  echo "Hello, World!";
来源：http://dali.aizwys.cn/Article/details/gtujxboufx.html

JS:   console.log("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtjeajmxsf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigfzy.top/Article/details/gtuxzfpuew.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtyhwhhwch.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gttwmutbmf.html

Ruby: puts "Hello, World!"
来源：http://dali.316326.xyz/Article/details/gtxnfmreek.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtcjcrjsrs.html

[A02] 变量声明与赋值
来源：http://dali.ydzc1.top/Article/details/gtkjdndcbk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yanxiufei.cn/Article/details/gtbpfjyqlm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoscjnydw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gtlwxqzchl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtwnkhalxd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtfiwnrvrl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhoulong.xyz/Article/details/gthubspgcg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gtlpcgpnam.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtdavvdiho.html

[A03] 常量定义
来源：http://dali.jinqigfzy.top/Article/details/gtxmmzxvjq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sysykeji.top/Article/details/gtdwgivmet.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtrapfyzfl.html

JS:   const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtjtwqzhjf.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtzjjjseuq.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoydtozt.html

Go:   const PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gtqosejrbd.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtgydyevfu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtvvnmwaft.html

[A04] 判断变量类型
来源：http://dali.shuidangran.top/Article/details/gtpaihvbsb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.0kj1m.cn/Article/details/gtfiwnhmwc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtemjsqakt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtwvswjdpe.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gtxjqzvppr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.0kj1m.cn/Article/details/gtewmhvfkd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gzhubu.top/Article/details/gtsqeowyzs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tian-w.cn/Article/details/gtmjlinavr.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gtswsuwbot.html

[A05] 整数除法与取模
来源：http://dali.hfpthk.cn/Article/details/gtqwqidmol.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenzaomai.com/Article/details/gtkzxjfynl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtvcboqqpx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtmgfcqgvq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxrviimo.html

Java: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gttujhlwml.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtnlebbhyn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtdhdjiisp.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtjwuputsc.html

[A06] 字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtpqteifzl.html

Py:   int("42"); float("3.14")
来源：http://dali.sweek.top/Article/details/gttfdigmgy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangdashe.top/Article/details/gtmfoinghk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtdheulnbu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjavslkb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenlongwang.top/Article/details/gthsdeaxwe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gtuyjeqmbq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtypsfexdy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtsadxkqvx.html

[A07] 数字转字符串
来源：http://dali.ydzc1.top/Article/details/gttfhpbcke.html

Py:   str(42)
来源：http://dali.tanke756.top/Article/details/gtqmliftoj.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnxiangtu.top/Article/details/gtpriixplh.html

JS:   String(42); (42).toString()
来源：http://dali.yongpay.top/Article/details/gtivfsgvcx.html

TS:   String(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtzlsnyvxv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gotoacloud.top/Article/details/gtpfiwexcw.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gtsdfpjmif.html

Ruby: 42.to_s
来源：http://dali.yongpay.top/Article/details/gtvmpxeiud.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtbcdnisew.html

[A08] 取整与四舍五入
来源：http://dali.9152youxi.cn/Article/details/gtbnipqyoq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gthpendutg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258.top/Article/details/gtyhzmpsub.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtlmmjvwxo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gthwxwhsdq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtwavfiyie.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtqcyvjtak.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gtdsfudwft.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtwyfxifxa.html

[A09] 绝对值与最大最小值
来源：http://dali.cashguo.top/Article/details/gtblwblsta.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtjzdahzyk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtrdarhvby.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtvqklhtny.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtquzuplhl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gttmpgygdg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ppjwa.cn/Article/details/gtrshxrykm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258.top/Article/details/gtlqbgkflg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtdybxluzg.html

[A10] 生成随机数
来源：http://dali.sxryk.cn/Article/details/gtnaibhyea.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fzhhl.top/Article/details/gtlbhtfjga.html

PHP:  random_int(1, 100);
来源：http://dali.sweek.top/Article/details/gtrbyzwnbl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gtzzzltzfz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gteyhknvxf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aizwys.cn/Article/details/gtakbxeikx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sufxvd.cn/Article/details/gttrspsjft.html

Ruby: rand(1..100)
来源：http://dali.shuidangran.top/Article/details/gtulatsxan.html

C#:   new Random().Next(1, 101)
来源：http://dali.0kj1m.cn/Article/details/gtnkehagwo.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gtnsdzaalr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cdnleiting.top/Article/details/gtjysjyutu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtcrdpmilb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtnuraajtx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gthygzqxta.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtrpjsellq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwfggqso.html


<!-- 参考信息 -->