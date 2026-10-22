代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gthfimdxkv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gtsspoqimw.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gtjxtoerjp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gaohongyu789.top/Article/details/gtxdqbbziv.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtguckybzd.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfatqquzo.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gtrdjchtrw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gtxneyizhf.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtyozcjikk.html

parse_ini_file("config.ini", true)
来源：http://dali.dashuyun.cn/Article/details/gtixxhcnbf.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtvvgenkaw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gtortlhvhk.html

[U75] PHP：依赖注入
来源：http://dali.feifeiyinyue.top/Article/details/gtibjlbifc.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gtxfqxwmvm.html

[U76] PHP：简单路由
来源：http://dali.tianlin.xyz/Article/details/gtvpjorzls.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gthlzfwgwo.html

[U77] PHP：模板渲染
来源：http://dali.shuidangran.top/Article/details/gtoecqgcpl.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gtayqxzndf.html

[U78] PHP：单元测试
来源：http://dali.tanke756.top/Article/details/gtctkweidx.html

composer require --dev phpunit/phpunit
来源：http://dali.kuanghao11.cn/Article/details/gtytbolzoz.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gttxxyhwzs.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtwbaybzgi.html

[U80] PHP：代码规范修复
来源：http://dali.zhongyouzk.top/Article/details/gtpvwmiowr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yonumen.top/Article/details/gtvlbhvarf.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gtuvkjmkin.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtmvlblaxg.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gtwuiekjcv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gtobrmfzca.html

[U83] JS：ES Module 导入导出
来源：http://dali.dashuyun.cn/Article/details/gtciyazamt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtaomtiivm.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gtbnvrzkje.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gttadpzehs.html

[U85] JS：可选链
来源：http://dali.tanke756.top/Article/details/gtruxvaeef.html

a?.b?.c
来源：http://dali.hammf.cn/Article/details/gtdrhadzcl.html

[U86] JS：空值合并
来源：http://dali.yangfankeji.com/Article/details/gtndqqnuzf.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gtynwbuefb.html

[U87] JS：解构默认值
来源：http://dali.cashguo.top/Article/details/gtwfsemixf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fzhhl.top/Article/details/gtwcnloexi.html

[U88] JS：对象展开合并
来源：http://dali.xylfe.cn/Article/details/gtfqlkvelb.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtceuyabwv.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gthyqmeomn.html

[...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtbksdovxn.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gthejykcmz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnlkijayt.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtbeblojnz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gtedhmfdcx.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gtszlcvkxa.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtgrbpkvon.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtpobuarfy.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gtytwygmof.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtpsbsnxqd.html

const double = x => x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtwcykqozw.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gtwvbkprjf.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtdyencref.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gtmxlrbxeq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtnlvmxcsb.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiwxjgsd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmylrbcqv.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtigtzdjhj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gtjxnfpvyf.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gtrhcgqzgd.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gtacjjbujn.html

[U100] JS：DOM 查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgpovggn.html

document.querySelector(".item")
来源：http://dali.wangshuangyany.cn/Article/details/gtssoyqmom.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gtllzllkmh.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gtalcrhghk.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtlfxwlzik.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gtphkqhvfl.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gtzwurukru.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gtlzpvryad.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gtbosgcyrs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtcjyjbote.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gtlflfqesa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gthspulkhb.html

[U106] JS：日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gttrjyfkti.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtbixzfqfl.html

[U107] JS：数字千分位
来源：http://dali.ydzc1.top/Article/details/gtulxhykgx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gtjingdnfs.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtwpcitbbr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gtochdcchd.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtpudotthw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtxmbwafun.html

[U110] JS：数组分块
来源：http://dali.jinqigufen.top/Article/details/gtgvlogerr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gtvwtwwqlj.html

[U111] JS：对象转 Map
来源：http://dali.dashuyun.cn/Article/details/gtvepcgqxc.html

new Map(Object.entries(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyciljwyd.html

[U112] JS：字符串补位
来源：http://dali.jlsjyb.cn/Article/details/gtmmltjndt.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxarscak.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gtjpmjddwf.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtjtjtgohc.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gtytxrdwyu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtzqsenkxg.html

[U115] JS：生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtmhbwgqtj.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtrmziluvu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtiawjxwlx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gtmmmrhaud.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtapskqxmy.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtaibygemq.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gtzpahodna.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtjgxcgapt.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtobonzfrh.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtgvqyvtoa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtwepvvfis.html

import.meta.env.VITE_API_URL
来源：http://dali.gotoacloud.top/Article/details/gtqsjqgzpp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiaiaytjm.html

统计汇总
来源：http://dali.xinyue.icu/Article/details/gtgzcvolip.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwpcythww.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gtpsbandrx.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gtrkycqnhs.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmusgkjm.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtcggpjbcb.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtddfqkehw.html

Java ........... 212
来源：http://dali.c1oappe.top/Article/details/gtezrpsbvs.html

Go ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtgraccnhv.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gtqlircpwb.html

C# ............. 212
来源：http://dali.daria6918.cn/Article/details/gtabtibxmz.html

C .............. 30
来源：http://dali.dianchejie.cn/Article/details/gtmqqnmsej.html

C++ ............ 30
来源：http://dali.gaohongyu789.top/Article/details/gtaruanqcn.html

SQL ............ 90
来源：http://dali.birdmap.top/Article/details/gtbapljcmb.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtvnardykf.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gtefsfqrso.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtaswjvntq.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gtcmflqnut.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtsgnfqcfl.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gtyxvaizbl.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtvdynmzcc.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gtfdbqrkox.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gtkffyxsjn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtvlhtezvh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtzlyqirkc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtzllhtgma.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtneqieygx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hammf.cn/Article/details/gtlwclohhx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gtmyzpatmn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtdpcvgbof.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtrsavkdnh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtvatokrwi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtepwlktve.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtwpdjkamg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtmixmltit.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtomaiskyc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gtarfrilcr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hammf.cn/Article/details/gtakrdfwvb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtqoapudvd.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gttwgmjull.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gtphtcbhqn.html

S C / C++ 专题                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmolbjxft.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gtitecyfhr.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gtkignevic.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtrjylirhr.html

合计                                  2106 条
来源：http://dali.zycfv.cn/Article/details/gtgllxenok.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtpykrxylc.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gtflkhthnp.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtiidbnavw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gtuzaclkhj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gtltbugbll.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj202588.top/Article/details/gtodjwgesm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shzxlz.cn/Article/details/gtydvcpotz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cqqwz.cn/Article/details/gtgbyrlbwy.html

—— 文件结束 ——
来源：http://dali.birdmap.top/Article/details/gtjryazbhq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtierhsdoy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gtflzvfeqy.html

Common Programming Examples Cheat Book
来源：http://dali.andypj.xyz/Article/details/gttrlemfvg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtajzjyepf.html

【收录内容】
来源：http://dali.gaohongyu789.top/Article/details/gtegnbtvtt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gtdbvxndwx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ybcxt.top/Article/details/gtkdgjahjv.html

SQL · Bash · C · C++
来源：http://dali.cqqwz.cn/Article/details/gtzzhpgkqn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pycfn.com/Article/details/gtyszvfacp.html

【使用说明】
来源：http://dali.sufxvd.cn/Article/details/gtrjyrebqs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtlzlgwhdb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.smart0.xyz/Article/details/gtmgtivver.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ehwqpu.com/Article/details/gtkjgnbfgz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gtuynstssu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtfekxwsnq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gtnssnbpyv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gtdhozhhgq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gtnabchfjr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtmsvawpiv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gaohongyu789.top/Article/details/gtmhxwijrd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgufenzy.top/Article/details/gtnmqgddbo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gtklkgjwsk.html

【文件统计】
来源：http://dali.gzhubu.top/Article/details/gttcdqlkxs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hysaishi.cn/Article/details/gtoinywkzl.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtnktuyvpe.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtotluiklt.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtiauktshg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtxdruilnh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjienwxxt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gttryiuocs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gtkrxkyprb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhoulong.xyz/Article/details/gtbbanmuyk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhoulong.xyz/Article/details/gtaqwafnzw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtnqwoxeul.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsepnytag.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtxyxdqjql.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gttuhrgkrf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gthhosjqvg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtsywevabz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gthbgikxwr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtrnjdpvaj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gtwqstnffp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtebbbhblq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tianlin.xyz/Article/details/gtsgdpbgsh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gthejttvnl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.bjfxy.top/Article/details/gtudifvitw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtzbtelmmz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtujgtszlx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkfzdtbkj.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gtduihamsb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpzeqpdyq.html

[A01] Hello World
来源：http://dali.c1oappe.top/Article/details/gtdicmgzxu.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtmxztrgyt.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gttapqnjwr.html

JS:   console.log("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgspjgko.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenlongwang.top/Article/details/gttxrqpeek.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gtfzlbjsws.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtyzgunzwb.html

Ruby: puts "Hello, World!"
来源：http://dali.guowangkeji.top/Article/details/gtsbhvpobo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtlzwtgkqd.html

[A02] 变量声明与赋值
来源：http://dali.cqqwz.cn/Article/details/gtpmxyawdc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xziqi.cn/Article/details/gtwoipedlz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtnwnjwnpg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtqjgzeeau.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.meibo888.top/Article/details/gthslpvmod.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtibqtdcmw.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gtuwnonbnt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ehwqpu.com/Article/details/gtuvbjcthh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtmrlowkqx.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtbeiaiafh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guowangkeji.top/Article/details/gthtsjkoit.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtntjbrhzn.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtuegpgbim.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtbxwrkpdq.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtxzzfetmw.html

Go:   const PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtovqfruui.html

Ruby: PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gtydifiboh.html

C#:   const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtljxludkz.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gtvwieprua.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxinkj.top/Article/details/gtfdjgozdh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiucofzoy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gtypowrzrs.html

TS:   typeof x; x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtgmvlbqqg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchljclxb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gtbhsjacmp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dianchejie.cn/Article/details/gtnykqwbpm.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gtfbldzitk.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gtbujjwgey.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gtqqktohui.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtzaptfxgb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtvmldvlxk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuxdamrv.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtwewfyvvh.html

Go:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtxtcewhcj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtfhpnmgqf.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtsefxpere.html

[A06] 字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtdxejeztl.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gthmhnhyqx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.bjfxy.top/Article/details/gtggidueyh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gtuoercntr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gtfjodzecl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuekpsikg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtdyvjorbp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gtpdkywzkf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtbnvykyab.html

[A07] 数字转字符串
来源：http://dali.zycfv.cn/Article/details/gtwnromtmg.html

Py:   str(42)
来源：http://dali.yj20258888.top/Article/details/gtilhitylz.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrblhgbhg.html

JS:   String(42); (42).toString()
来源：http://dali.cqqwz.cn/Article/details/gtgfkyomhh.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gtjmltpvny.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gteynkuysn.html

Go:   strconv.Itoa(42)
来源：http://dali.havefunace.top/Article/details/gtfohpaijo.html

Ruby: 42.to_s
来源：http://dali.redwolf501.top/Article/details/gttmwlbihp.html

C#:   42.ToString()
来源：http://dali.jqgufenzy.top/Article/details/gtravuizra.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gtxjeuxdpy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtdflehpfl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gtlaukvbyc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtwezkiujl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gtucitkwry.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtvbnwnxlq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtkdxgxhmq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yonumen.top/Article/details/gtutdydnnu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtmtfsyybm.html

[A09] 绝对值与最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtqdrgmfax.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtuslimdwy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtkfrtvfdx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gteigsgruj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtifympemm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtlxagwvtf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgfzy.top/Article/details/gtrfohvwqk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigfzy.top/Article/details/gtcbyclfwo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gteyxxwnbd.html

[A10] 生成随机数
来源：http://dali.shzxlz.cn/Article/details/gtpbauklbv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoksnwafz.html

PHP:  random_int(1, 100);
来源：http://dali.chenzaomai.com/Article/details/gteubgkzeo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtbztsqqra.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzfnxejpd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtrwhetmzm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yonumen.top/Article/details/gtckihrgxq.html

Ruby: rand(1..100)
来源：http://dali.andypj.xyz/Article/details/gtyvtyveld.html


<!-- 参考信息 -->