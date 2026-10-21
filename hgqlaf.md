代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtmnsywjqi.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gthifcszmh.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gticginexl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtsjzddiyf.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gtrobwdfhg.html

parse_ini_file("config.ini", true)
来源：http://dali.sxryk.cn/Article/details/gtlsbafvep.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtydmuswwv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gtbnizrpdq.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gtrsgfzyjp.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtncuoypgd.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gtdozvwuoj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gteewoyhlw.html

[U77] PHP：模板渲染
来源：http://dali.nanxinkj.top/Article/details/gthqrgnwcy.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gtlrxtebro.html

[U78] PHP：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtlxpaxtzc.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gtvrtbroqr.html

[U79] PHP：静态分析
来源：http://dali.tanke756.top/Article/details/gthgvevvvw.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gtajempyqh.html

[U80] PHP：代码规范修复
来源：http://dali.yanxiufei.cn/Article/details/gtihqvunsx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhjqfybp.html

[U81] JS：初始化项目
来源：http://dali.vqdsnc.cn/Article/details/gtwtoppxsn.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gtjsjyvihx.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gtxujswsit.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenzaomai.com/Article/details/gteuiupqpn.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtdwycmcgu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtpouvpado.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gtpbgmzzxp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gteiszbtqg.html

[U85] JS：可选链
来源：http://dali.cheryme.top/Article/details/gtimxvmehv.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gtgknrfpxx.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gtklgbfcvq.html

a ?? b
来源：http://dali.hnqzz.top/Article/details/gttuuvyaay.html

[U87] JS：解构默认值
来源：http://dali.zhongyouzk.top/Article/details/gtgffrbfpz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xziqi.cn/Article/details/gtrgmytlfz.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gtdghhzpdo.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gtkuxzymxg.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gthssyvuoy.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtyfpvsypu.html

[U90] JS：数字数组排序
来源：http://dali.yangfankeji.com/Article/details/gtqmjfurli.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtchwikjvr.html

[U91] JS：对象键值遍历
来源：http://dali.dashuyun.cn/Article/details/gtwgukfwzy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tian-w.cn/Article/details/gtawrtyuqz.html

[U92] JS：深拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtdoejwiky.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtjarqtbnp.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gteqfxvqqt.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gtrjjmwixb.html

[U94] JS：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtborelwwv.html

const double = x => x * 2;
来源：http://dali.cheryme.top/Article/details/gtuyjxmujy.html

[U95] JS：Promise 包装
来源：http://dali.hfpthk.cn/Article/details/gtchqdiwlm.html

new Promise((resolve, reject) => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwcohced.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gtqljlfavg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtogcbqnot.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gtokibgvec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gttuclklgr.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gtxgewfksx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daxiang520.top/Article/details/gtbbvrknks.html

[U99] JS：事件监听
来源：http://dali.jinghuilouyu.cn/Article/details/gtiummnmlg.html

el.addEventListener("click", e => {})
来源：http://dali.c1oappe.top/Article/details/gtxzhlumsn.html

[U100] JS：DOM 查询
来源：http://dali.hnxiangtu.top/Article/details/gtdpceatil.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gtilpgdrrp.html

[U101] JS：classList 操作
来源：http://dali.smart0.xyz/Article/details/gteavyshra.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gtdernqyds.html

[U102] JS：本地存储
来源：http://dali.mhx1999.top/Article/details/gtrnmspqen.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbixkldaq.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gtpegmkodu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tian-w.cn/Article/details/gtdieislss.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gtviyafqev.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtfhinlzof.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtyvvgjvmh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xinyue.icu/Article/details/gtnhuwrohr.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtaocjwoen.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gtgzbennmy.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtoscowiyw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtdxvchajq.html

[U108] JS：随机整数
来源：http://dali.nanxinkj.top/Article/details/gtshrcpcqv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxtjgytb.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gttsbmjepx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsxgoqzu.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxzpccqg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtdvrxobta.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gtabrziteh.html

new Map(Object.entries(obj))
来源：http://dali.chenzaomai.com/Article/details/gtyvfcqvvw.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gtgkgmbhpw.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtbppmdfpw.html

[U113] JS：正则替换全部
来源：http://dali.snrcjt.cn/Article/details/gtfohyheuq.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtnbgolklq.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gtmxxvieyt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtkpnrkaly.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gthhibzxew.html

crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtnrydlpow.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gtfiyizyfy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gtbsydcuna.html

[U117] JS：单元测试
来源：http://dali.yueranfly.top/Article/details/gtzkvnzzem.html

npm i -D vitest;  npx vitest
来源：http://dali.feifeiyinyue.top/Article/details/gtfsvyuudi.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtbyhycjaw.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtiirflkqj.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtfvyantfn.html

npx vite build
来源：http://dali.hnxiangtu.top/Article/details/gtdheqrgxu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gtjwyrkkng.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gthtfblgeq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrytqdesu.html

统计汇总
来源：http://dali.meibo888.top/Article/details/gttsyfmour.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfitpvuq.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gtlwivczxe.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtmwnravbx.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gtkvraricc.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtwhirille.html

TypeScript ..... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtaskfmiza.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gttvwhrytg.html

Go ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtecnxvptc.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gtavbffmou.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtmsbvnpgm.html

C .............. 30
来源：http://dali.xylfe.cn/Article/details/gtpvkdxxkj.html

C++ ............ 30
来源：http://dali.nwbrower.top/Article/details/gtthvlfxir.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gtgszkepuv.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtuscefjkd.html

Kotlin ......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtrfcrlwcj.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtjbsrrlew.html

Lua ............ 10
来源：http://dali.aibaodan.cn/Article/details/gtgvdofbpa.html

Perl ........... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtvvaewwvy.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtbyduqkay.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtjcwbgpvn.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtgjsimsjc.html

按章节统计：
来源：http://dali.xuetiantiany.cn/Article/details/gtuimkvjxj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gtyznlifpp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtfetbyupn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtlqwgxumu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfffnznd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gtxsacruoe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtikzojbtf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtojfavfyf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtscrlaoys.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtdzykusbk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtktdjyrnb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtcfplcovu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtmjfezeao.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gthvahmhiw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtdbnnqutr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gtmwrstuvs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtrskvsxup.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gtepvkqteu.html

R Bash 专题                             80
来源：http://dali.ydzc1.top/Article/details/gtrunpxckq.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gtqezdqhva.html

T 其他语言补充                          60
来源：http://dali.havefunace.top/Article/details/gtdludtusk.html

U 高频实用片段                         120
来源：http://dali.gogol.net.cn/Article/details/gtxkbrugtn.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtzufxaehe.html

合计                                  2106 条
来源：http://dali.9152youxi.cn/Article/details/gthhqwtpxi.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtqkhpzfmv.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gthodzjnxk.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtvwwrvqnk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shzxlz.cn/Article/details/gtuxcuqser.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sysykeji.top/Article/details/gtpupbmasa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.bjfxy.top/Article/details/gtycjecjqk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cashguo.top/Article/details/gtvfprciux.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hysaishi.cn/Article/details/gtfudabsja.html

—— 文件结束 ——
来源：http://dali.0kj1m.cn/Article/details/gtpchhdcis.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtadshijsw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gtcwxsfzsu.html

Common Programming Examples Cheat Book
来源：http://dali.gogol.net.cn/Article/details/gtbpzfdchu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdxxonkjl.html

【收录内容】
来源：http://dali.ybcxt.top/Article/details/gtmkkwdvor.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zycfv.cn/Article/details/gttljtzwgl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuanzx.com/Article/details/gtukqpjzjf.html

SQL · Bash · C · C++
来源：http://dali.yuanzhike.top/Article/details/gtpwuetxgk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gtorwmmecx.html

【使用说明】
来源：http://dali.shanyushiyangtech.top/Article/details/gtczerjsfz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hammf.cn/Article/details/gtbcumpczv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhengqikj.top/Article/details/gtipyjblax.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gtfisqbdoi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gtzlwyjdej.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtyqlefbgb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gtyghaiyld.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtedknnwsg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gaohongyu789.top/Article/details/gtfffeclxs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.tianlin.xyz/Article/details/gtqdbbiicw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yonumen.top/Article/details/gtkusssjaw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shzxlz.cn/Article/details/gtnduaeerx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gtcwkadvui.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gttdrrhjak.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.birdmap.top/Article/details/gtejaebtme.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtvrpncrrs.html

目  录
来源：http://dali.kuanghao11.cn/Article/details/gtvspszcyf.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtlkynksqv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtwexbyfrv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtxhdidpnh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtdhflkcgj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gtjxglhmtb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsipznpam.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gtisinopfs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtfsqsmgsu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtcgakcvtn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuhhtzxl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtxaiokvnq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtzntwspzp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtroauqhhy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtkrvopefk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtddtlcqmg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.iojbl.cn/Article/details/gtzhaebiic.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtkehnumqx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.iojbl.cn/Article/details/gtmwtmjapo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuxming.cn/Article/details/gtdrrhwopy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazlpyucb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtbgixlzqk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtkqpswxwr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuirutpb.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gtkvhnegqz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtliomvkqo.html

[A01] Hello World
来源：http://dali.snrcjt.cn/Article/details/gtymiecgzh.html

Py:   print("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtikmeakvv.html

PHP:  echo "Hello, World!";
来源：http://dali.jlsjyb.cn/Article/details/gtnudhmeol.html

JS:   console.log("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtcbnyehyk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gtvbzzcksu.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gttjztvsvh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gthvnlokbg.html

Ruby: puts "Hello, World!"
来源：http://dali.hysaishi.cn/Article/details/gtdirmhish.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtsgrmhnuc.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gtpciathup.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhoulong.xyz/Article/details/gtfovaytqm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ivvv.top/Article/details/gtcvxuaxsv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.c1oappe.top/Article/details/gtgoahppfz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtrevkkeni.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtwuzjcwiw.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgfzy.top/Article/details/gtllhlvfqk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yangfankeji.com/Article/details/gtecvsufes.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gtvbhepqgo.html

[A03] 常量定义
来源：http://dali.aibaodan.cn/Article/details/gtatdwedxh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gtcjgglcot.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtcexskstj.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtdgewsdus.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtptaqidig.html

Java: static final double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtvbniprwf.html

Go:   const PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gtnnfwsmpi.html

Ruby: PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gtikxkgrfe.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtolnjzmao.html

[A04] 判断变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtoqovxtmi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuetiantiany.cn/Article/details/gtegpudgdm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgufenzy.top/Article/details/gtpjjlrqud.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtbdrwycjy.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gtfnrallav.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj202588.top/Article/details/gtpqupdlmy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gtkgigezhk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gtkmtaftgp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gtkfbbgxew.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gtatybilla.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepzxzxza.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtfqwzdynr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtraqgnnuh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtnfceathf.html

Java: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtumpgkurf.html

Go:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtrrjqgpzt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtzgexwtny.html

C#:   7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtxrzlwmds.html

[A06] 字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtvrejrekz.html

Py:   int("42"); float("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtxymlpgik.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cucudq.cn/Article/details/gtztasjxxm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtifatdqyg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gthohcjfwx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtughqudsk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtptmeaxrt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.snrcjt.cn/Article/details/gtzzqpgeaq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtcnoqkozt.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gtcqxmfuls.html

Py:   str(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtaspyfnzc.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbzomfcz.html

JS:   String(42); (42).toString()
来源：http://dali.guowangkeji.top/Article/details/gtraknfsgf.html

TS:   String(42)
来源：http://dali.vqdsnc.cn/Article/details/gtchyvwnnd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gtanipazqg.html

Go:   strconv.Itoa(42)
来源：http://dali.snrcjt.cn/Article/details/gtojrbhudy.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gtgdeonycv.html

C#:   42.ToString()
来源：http://dali.aibaodan.cn/Article/details/gttsacnruv.html

[A08] 取整与四舍五入
来源：http://dali.9152youxi.cn/Article/details/gtkkkbddjd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiqbrhxw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.bjfxy.top/Article/details/gthrrnqivi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtcquahwrm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gtlwvecuge.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtbnehjrsg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtofrfiklk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pengpengdd.cyou/Article/details/gtavsokutw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtzetlsszr.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtwvekzbjh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtbdqjdyjq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtccbnwjcn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtdbvjqkzl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtfzuunawu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtbvsnorht.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jianghu66.top/Article/details/gtarexbkfq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.guowangkeji.top/Article/details/gtjsiqdshc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtrcksxboq.html

[A10] 生成随机数
来源：http://dali.cqqwz.cn/Article/details/gtcbosakgv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgufenzy.top/Article/details/gtsheabhyp.html

PHP:  random_int(1, 100);
来源：http://dali.mhx1999.top/Article/details/gtisbnlwfl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtjvebesma.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtfkkvyttd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtmxgsihjh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigufen.top/Article/details/gttogqidrw.html

Ruby: rand(1..100)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmabuslx.html

C#:   new Random().Next(1, 101)
来源：http://dali.wangshuangyany.cn/Article/details/gtgjlslzww.html

[A11] 条件表达式（三元）
来源：http://dali.yangfankeji.com/Article/details/gtuwxvzeib.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shuidangran.top/Article/details/gtnorekuxo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtlbdzsybk.html


<!-- 参考信息 -->