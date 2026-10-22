代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gtmbbrtvoo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gtdyutlazd.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtavqurvky.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gtcenitsup.html

[U69] PHP：PDO 预处理
来源：http://dali.haohaochexian.top/Article/details/gtgfjnhrpp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gtmgtoatvr.html

[U70] PHP：PDO 事务
来源：http://dali.andypj.xyz/Article/details/gthrkeyhnw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxftbdkxn.html

[U71] PHP：抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtckzodoid.html

throw new RuntimeException("失败", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtzocktrmr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gtrfopjoih.html

error_log("失败: " . $e->getMessage());
来源：http://dali.vqdsnc.cn/Article/details/gtsvuarwtv.html

[U73] PHP：读取 ini 配置
来源：http://dali.sufxvd.cn/Article/details/gtmgiuxtrp.html

parse_ini_file("config.ini", true)
来源：http://dali.yongpay.top/Article/details/gtgpdzarcg.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtckxkmrmp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gtbvglkvan.html

[U75] PHP：依赖注入
来源：http://dali.jinqigfzy.top/Article/details/gtjepsfgvb.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gttjpxtlpp.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gtxraypryx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gttwmtxdpw.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtlocyccbl.html

composer require twig/twig
来源：http://dali.zdqjudy.top/Article/details/gtsoqpstuv.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtmcvobocx.html

composer require --dev phpunit/phpunit
来源：http://dali.aizwys.cn/Article/details/gttfafwutc.html

[U79] PHP：静态分析
来源：http://dali.sysykeji.top/Article/details/gtrkwympqy.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gtwdogtcvb.html

[U80] PHP：代码规范修复
来源：http://dali.chenlongwang.top/Article/details/gtwlccwmpf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gtkedowmml.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gtliihgdxv.html

npm init -y;  npm i express
来源：http://dali.yuxming.cn/Article/details/gtrocizmqq.html

[U82] JS：package.json 脚本
来源：http://dali.nanxinkj.top/Article/details/gtwbvllqrt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtalwjuagw.html

[U83] JS：ES Module 导入导出
来源：http://dali.shangyingyoupin.top/Article/details/gtrlgyhyem.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtucjxworg.html

[U84] JS：CommonJS 写法
来源：http://dali.smart0.xyz/Article/details/gtptjmdzpr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtqenyywqf.html

[U85] JS：可选链
来源：http://dali.iojbl.cn/Article/details/gtwqneqswl.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gttswxnpam.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtntxzrfho.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gtqrqyvmvb.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gtxtrgixdy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cashguo.top/Article/details/gtulqeuqzn.html

[U88] JS：对象展开合并
来源：http://dali.haohaochexian.top/Article/details/gtprzvtmqj.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gtfpxjmzzz.html

[U89] JS：数组去重
来源：http://dali.guowangkeji.top/Article/details/gtjayxxixb.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtugcsrvsd.html

[U90] JS：数字数组排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtvquiddcb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtedjzgbme.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gthlvntalt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtunxjrrdj.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gtcamqpogg.html

structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtkyfffeui.html

[U93] JS：模板字符串
来源：http://dali.redwolf501.top/Article/details/gtfgvufswp.html

`共 ${n} 条`
来源：http://dali.gaohongyu789.top/Article/details/gtdkploakw.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtwcejvvqi.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gtkfsbnhgo.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gtaabwaaot.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gtzjyypddv.html

[U96] JS：async/await 与异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmwbnbtp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtweprbiez.html

[U97] JS：并发请求
来源：http://dali.yj20258.top/Article/details/gtnszoegdf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtelduouit.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtoohdgegu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gtxvsjkihl.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gthfgfmlqw.html

el.addEventListener("click", e => {})
来源：http://dali.yanxiufei.cn/Article/details/gtsxfbyjmf.html

[U100] JS：DOM 查询
来源：http://dali.zhoulong.xyz/Article/details/gtqkmljimn.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidmfpnoy.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gtqbihqmaa.html

el.classList.toggle("active")
来源：http://dali.hfpthk.cn/Article/details/gtcoapqjlg.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtlxxgjnxa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gtlbkvyfbt.html

[U103] JS：定时器
来源：http://dali.tanke756.top/Article/details/gtjonhfmef.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cucudq.cn/Article/details/gtigsebujg.html

[U104] JS：防抖
来源：http://dali.cheryme.top/Article/details/gtxllwhsgh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtsarvklcn.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gtqsfjquzs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtmfytayjn.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gtlkderfun.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gtjfiewxnp.html

[U107] JS：数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtdvftdxog.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtsxjrxwmc.html

[U108] JS：随机整数
来源：http://dali.sweek.top/Article/details/gtjpnzamuk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.svipenyu.cn/Article/details/gtdlwjqmay.html

[U109] JS：数组分组
来源：http://dali.hywenlv.cn/Article/details/gtrzrzidzt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtsoctsepx.html

[U110] JS：数组分块
来源：http://dali.jqgufenzy.top/Article/details/gtuuhdklkw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gtlejixbbp.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gtnqvnqarp.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvekgxktd.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzuvirhl.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtdpfmczqi.html

[U113] JS：正则替换全部
来源：http://dali.nanxuanxn.top/Article/details/gttnayfjmf.html

s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtrefcwlcb.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gtnpgmeqhp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gteegwwnsm.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtfpqlcuuj.html

crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtaeuditeu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gtxmpjsgqz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gthrqlxeci.html

[U117] JS：单元测试
来源：http://dali.316326.xyz/Article/details/gtcoeltcdv.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gtxagjrlhb.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gtnixonczh.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gtcdyerfib.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gtqgwttlor.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gtidvndfcu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gtilbfntnj.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gtfupbwwok.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtncbavwnx.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gtyucuspba.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquvqmaax.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtabrqqiqp.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gtcaczpoxv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gtudbfbchq.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gtzmmbzeok.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtpxomyncu.html

Java ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtnywjgrvo.html

Go ............. 212
来源：http://dali.shuidangran.top/Article/details/gtuzpqxkxx.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtbyscfrme.html

C# ............. 212
来源：http://dali.tian-w.cn/Article/details/gtfetyjbtn.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gtwzixhdtd.html

C++ ............ 30
来源：http://dali.chenlongwang.top/Article/details/gtksrtsaxe.html

SQL ............ 90
来源：http://dali.cheryme.top/Article/details/gtoihullhn.html

Bash ........... 80
来源：http://dali.tianlin.xyz/Article/details/gttectroay.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gtajqnmtrm.html

Swift .......... 15
来源：http://dali.cashguo.top/Article/details/gtovibkunq.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtbnpekotr.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtrgzudqyi.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtmylqmuth.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gthhqxtgiz.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gtorkkoxaa.html

按章节统计：
来源：http://dali.nanxuanxn.top/Article/details/gtirslvhyb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtyscigncw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtfmwvegvr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtanqqslpj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtgwlsrcrl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtqbuguchy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtrkefolbh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtwxicdrlb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtfuficqgq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtkwxbqzkf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtxlggenzp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtilvmiulr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtorqcsroc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtkcimpvqo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtilfqqumj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwjksjqs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtlhlvxpwv.html

Q SQL 专题                              90
来源：http://dali.vqdsnc.cn/Article/details/gthlytnino.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gtndixbgky.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gtbzhksgzo.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gtlasatlzt.html

U 高频实用片段                         120
来源：http://dali.dashuyun.cn/Article/details/gtjrwswpvo.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtmcczldnj.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gtlrwwavda.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtezompkhj.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gtoxuavpej.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtmhbvllia.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gtsutcuwhx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hysaishi.cn/Article/details/gtzlxcffew.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ivvv.top/Article/details/gtgcltrvgy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jianghu66.top/Article/details/gtlbdqmqhf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqcxydfs.html

—— 文件结束 ——
来源：http://dali.sweek.top/Article/details/gtaiyrhbuk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtprdlcoot.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gtvbarudxr.html

Common Programming Examples Cheat Book
来源：http://dali.jinghuilouyu.cn/Article/details/gturkbklwt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcosootxz.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gtizejfuvt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.iojbl.cn/Article/details/gtvkjgwaqx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gtgdtzliwi.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gtytrsjeep.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cucudq.cn/Article/details/gtrgruumdz.html

【使用说明】
来源：http://dali.cqqwz.cn/Article/details/gthxkraxtr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cashguo.top/Article/details/gtczygjppc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aibaodan.cn/Article/details/gtgmytpcag.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuxming.cn/Article/details/gtcugvnvwz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daria6918.cn/Article/details/gtqnvsilbx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gthliwogut.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gtaagxdsit.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sxryk.cn/Article/details/gtnypbndui.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtxfcufqgl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sxryk.cn/Article/details/gtlvfabkam.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yongpay.top/Article/details/gtpcixtvph.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gaohongyu789.top/Article/details/gtpxfrixsi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gtppitiupt.html

【文件统计】
来源：http://dali.meibo888.top/Article/details/gtkbohufus.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.havefunace.top/Article/details/gtaiofqmmq.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtjzxeuiah.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gtqlbgrudy.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtztfkopma.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtzktreafl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtqmtmuhrq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtadmwotsl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daria6918.cn/Article/details/gtyqjydcmb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhixingplan.top/Article/details/gtwzlwlfqt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtffmchdrj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gthkvkmmez.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtbksakhvm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtuwbjrcud.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtmynqbndq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtsoqhlifr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gttdqavylm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtbpgmseny.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtgehdhuda.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgfzy.top/Article/details/gtosqquqox.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtsbedtkjw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ppjwa.cn/Article/details/gtvqniqhcw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daria6918.cn/Article/details/gtojvslcui.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsbfdbab.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gthkitqcda.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gtjbxljwvy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtiwifntpr.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gtulmlelqe.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwhmfcawl.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtvcxmcyvx.html

Py:   print("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gtnhbtfccn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhiwuduotai.top/Article/details/gtezmjetxw.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtbyxrrvuz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258888.top/Article/details/gtjxwudxub.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtjduccqsa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gttcqayrhm.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gtgjiozvtb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtpdsxiqvx.html

[A02] 变量声明与赋值
来源：http://dali.sweek.top/Article/details/gtwvjuuanx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgufenzy.top/Article/details/gtsgaleeud.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jianghu66.top/Article/details/gtxkvjzrib.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gtkbonvhjx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shzxlz.cn/Article/details/gtvvydezmv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtpyfyhwci.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigfzy.top/Article/details/gtotjinhoi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ybcxt.top/Article/details/gtanekqxni.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtacxgwhwo.html

[A03] 常量定义
来源：http://dali.shangyingyoupin.top/Article/details/gtvunxwshm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gtfmuljvzx.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtyzgwidbq.html

JS:   const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gthlmuvfan.html

TS:   const PI: number = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtiubcgkki.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtiktsvyhw.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gtfmgxpqio.html

Ruby: PI = 3.14159
来源：http://dali.yvedp.cn/Article/details/gtyvaxzskw.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtwxvpcdpc.html

[A04] 判断变量类型
来源：http://dali.meibo888.top/Article/details/gtlfeckqyz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxbtpxll.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtswaemodm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sweek.top/Article/details/gtspzloeld.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtmaxmbloy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gtlgpjnnay.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ivvv.top/Article/details/gttslgxmen.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gtyyktzaky.html

C#:   x.GetType().Name; x is int
来源：http://dali.ppjwa.cn/Article/details/gtgrmfvdkz.html

[A05] 整数除法与取模
来源：http://dali.sweek.top/Article/details/gtbcbwblqc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gtsmfvdnyz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gthzifhdxd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtrxjjowlw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtqidlmmlm.html

Java: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtvhhtnsqj.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gteqcdkyrm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtxbuntvei.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtidsgofuq.html

[A06] 字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtnlvojvvy.html

Py:   int("42"); float("3.14")
来源：http://dali.nwbrower.top/Article/details/gttsamblnr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtkqzpkoje.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gtjybktysv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtbpmfhhdj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gzhubu.top/Article/details/gtotjupbmh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yvedp.cn/Article/details/gtkyqnhcrj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuanzx.com/Article/details/gtldyrbnbx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gtwvnqkacb.html

[A07] 数字转字符串
来源：http://dali.yvedp.cn/Article/details/gtymvvnwav.html

Py:   str(42)
来源：http://dali.gogol.net.cn/Article/details/gtiydbhlcf.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnxiangtu.top/Article/details/gtiswjdklo.html

JS:   String(42); (42).toString()
来源：http://dali.sufxvd.cn/Article/details/gthxrezfri.html

TS:   String(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxpmmpxk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gtptvahgou.html

Go:   strconv.Itoa(42)
来源：http://dali.guannengcc.top/Article/details/gtecfcxnif.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gtecfirseu.html

C#:   42.ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtpmniwssn.html

[A08] 取整与四舍五入
来源：http://dali.wangdashe.top/Article/details/gtutwaiwmi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtliqsarfm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gttxlooouy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtgowfvfoa.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hysaishi.cn/Article/details/gtbodizuss.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtnajaojrx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtssmkpqqg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xinyue.icu/Article/details/gtdmarojxh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtlpppjwga.html

[A09] 绝对值与最大最小值
来源：http://dali.yonumen.top/Article/details/gtmqissmia.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtncxcgiso.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtcyxlrhmb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtiuhfrcbf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtssjyyhfn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtxlwrazog.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hammf.cn/Article/details/gtjxmvvllj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.c1oappe.top/Article/details/gthxkkjzfv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtpfpsoxze.html

[A10] 生成随机数
来源：http://dali.aibaodan.cn/Article/details/gtalhesofd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shzxlz.cn/Article/details/gtlkesbhsn.html

PHP:  random_int(1, 100);
来源：http://dali.dashuyun.cn/Article/details/gtqfkxjoll.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yvedp.cn/Article/details/gtjbyzytbg.html


<!-- 参考信息 -->