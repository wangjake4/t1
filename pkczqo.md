代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.gogol.net.cn/Article/details/gt2tohfzzsq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gt2civxhudj.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvbnqmlw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gt2nvvpdute.html

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gt2lylkjzyz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fojbynji.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhnhvkgd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gt2httlbspp.html

[U71] PHP：抛出异常
来源：http://dali.havefunace.top/Article/details/gt2mweyfgam.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2eacrbbye.html

[U72] PHP：写错误日志
来源：http://dali.yanxiufei.cn/Article/details/gt2kmqwpygx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gt2cinseblp.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gt2wnhqaqih.html

parse_ini_file("config.ini", true)
来源：http://dali.gzhubu.top/Article/details/gt2jlogoxmm.html

[U74] PHP：读取环境变量
来源：http://dali.tian-w.cn/Article/details/gt2caqdknat.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gt2woaixcgl.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gt2laoasrth.html

composer require psr/container
来源：http://dali.yongpay.top/Article/details/gt2mzjvmzyd.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gt2owjzlytj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebmkdufv.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gt2kbxbefhr.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gt2hwgclbsp.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gt2jludyozz.html

composer require --dev phpunit/phpunit
来源：http://dali.sufxvd.cn/Article/details/gt2otjxbltg.html

[U79] PHP：静态分析
来源：http://dali.ehwqpu.com/Article/details/gt2ujxaekdt.html

composer require --dev phpstan/phpstan
来源：http://dali.shzxlz.cn/Article/details/gt2edludzzf.html

[U80] PHP：代码规范修复
来源：http://dali.bjfxy.top/Article/details/gt2hijikdco.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gt2kxbocrbu.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gt2dasdslyl.html

npm init -y;  npm i express
来源：http://dali.dashuyun.cn/Article/details/gt2tuodtleq.html

[U82] JS：package.json 脚本
来源：http://dali.nanxinkj.top/Article/details/gt2hjhjqomh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aibaodan.cn/Article/details/gt2eqtkdgpl.html

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gt2kowxwiup.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2ymiisrri.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gt2nlwbmlhn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.iojbl.cn/Article/details/gt2fwceqhtg.html

[U85] JS：可选链
来源：http://dali.yongpay.top/Article/details/gt2qotgenwv.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gt2zyqiazpe.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gt2uyozflvp.html

a ?? b
来源：http://dali.tianlin.xyz/Article/details/gt2qjyegphf.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpjeohig.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gt2ujnefqfx.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gt2tijklcwf.html

{ ...a, ...b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2goaswwia.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gt2oxqcievd.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcrfdyfq.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gt2mzxkcmng.html

[...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2aoqralid.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvykjotn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gt2thihhzbe.html

[U92] JS：深拷贝
来源：http://dali.sysykeji.top/Article/details/gt2awukqyvl.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2tznnvskl.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2apoommmw.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gt2tphwyzev.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gt2hxplakam.html

const double = x => x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2uctdjhrm.html

[U95] JS：Promise 包装
来源：http://dali.dianchejie.cn/Article/details/gt2rtcvknmf.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsnrypqr.html

[U96] JS：async/await 与异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2qafodkmv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2tngqiisf.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gt2kfbvslim.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltvflqws.html

[U98] JS：fetch 带 JSON
来源：http://dali.smart0.xyz/Article/details/gt2nzmceloj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gt2umlrqgsm.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gt2gkfdsnyu.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gt2quomjwjt.html

[U100] JS：DOM 查询
来源：http://dali.zhixingplan.top/Article/details/gt2kxznrhgw.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gatxiory.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gt2wbppxohq.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gt2mgromgpn.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gt2kqmmjixg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gt2eclalmim.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gt2wldrnfvg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gt2rmxnhhgu.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gt2vqokejba.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2wvbcyxyu.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifpokwug.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gt2yatjmedq.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxclsvkl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gt2kayctixh.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gt2ueqaglnf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guannengcc.top/Article/details/gt2jtxrnron.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gt2ijemzjhy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfhfjgca.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gt2tdjwplae.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gt2ubjqibkl.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gt2xxbgdlno.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gt2hpscuiqs.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocldbzrw.html

new Map(Object.entries(obj))
来源：http://dali.hammf.cn/Article/details/gt2jpqidicf.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gt2hboqgrqb.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2ingcjtwx.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gt2nubgbiif.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuexcfjn.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gt2bhnxlwst.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2hdbttsdo.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2gbnrkrjf.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2iejqlgcf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gt2xfwesahi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gt2rtbyqcar.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlhuzprn.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gt2cpiqmgry.html

[U118] JS：开发服务器
来源：http://dali.0kj1m.cn/Article/details/gt2julwmtks.html

npm i -D vite;  npx vite
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksyaynuk.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gt2hxdxepbl.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gt2hciwfxqy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jyoumei.cn/Article/details/gt2qosmuvlp.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gt2phdknakm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmsgkwbc.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gt2nasxkpbp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2snzbbbim.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gt2dpqbisib.html

Python ......... 252
来源：http://dali.fzhhl.top/Article/details/gt2azffydmt.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gt2miovwaqb.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gt2nowzlftu.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gt2vqbnhpxp.html

Java ........... 212
来源：http://dali.fzhhl.top/Article/details/gt2pzmrqocy.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gt2whqhighk.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gt2tlheqofa.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gt2agwnfbxi.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gt2pamecsst.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2vvqcihdj.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gt2sxfrtuuj.html

Bash ........... 80
来源：http://dali.xuetiantiany.cn/Article/details/gt2thijukou.html

Kotlin ......... 15
来源：http://dali.daria6918.cn/Article/details/gt2yplbjoxs.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gt2qcxavdji.html

Lua ............ 10
来源：http://dali.jianghu66.top/Article/details/gt2qoenseak.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gt2expvocov.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gt2jvbennow.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztwqtjzj.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gt2mkdehpcn.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gt2vqvgrvvi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gt2ivfvnzta.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbxtlgas.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2amvishbd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gt2cokgiwba.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gt2mksxlvwy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gt2kakvtqys.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2queejdad.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqznxzpp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2zgmpgxfy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gt2uhwyzpoo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2ttuxwbkm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2bnfbrxbn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2whtjakzn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gt2rwwvuyug.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gt2yrtnucdw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2lqyimmnq.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gt2kcjfcovl.html

R Bash 专题                             80
来源：http://dali.zycfv.cn/Article/details/gt2xpjxprrj.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gt2bbuilhjy.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gt2onvyqgue.html

U 高频实用片段                         120
来源：http://dali.tian-w.cn/Article/details/gt2pndvnlko.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2hdvdlwzt.html

合计                                  2106 条
来源：http://dali.kuanghao11.cn/Article/details/gt2wodqfxrt.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2ofmuyofh.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gt2dsraoico.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2rwxgzdjc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gzhubu.top/Article/details/gt2mtensxxx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ivvv.top/Article/details/gt2fuhidygu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fengsongda.top/Article/details/gt2wevwankz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gt2fnlxzgfl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gt2llvxesmw.html

—— 文件结束 ——
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbhldmcc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rboachcr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gt2qxafiiuw.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrjgbbft.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rfkqztli.html

【收录内容】
来源：http://dali.nwbrower.top/Article/details/gt2hyocmkvy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.meibo888.top/Article/details/gt2ofzesnig.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.kuanghao11.cn/Article/details/gt2vifwrepe.html

SQL · Bash · C · C++
来源：http://dali.pycfn.com/Article/details/gt2dhhndoha.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gt2khoouscw.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gt2pgpebprx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xinyue.icu/Article/details/gt2samiodhn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.redwolf501.top/Article/details/gt2rndjzsgi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gt2aqsplvxk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hysaishi.cn/Article/details/gt2reiqnvyg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yanxiufei.cn/Article/details/gt2abbphmbp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hywenlv.cn/Article/details/gt2zukcjmpu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gt2csjgkllt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gt2mahkrewg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.smart0.xyz/Article/details/gt2xvevsbqx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.andypj.xyz/Article/details/gt2vgqijqii.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gt2woigojqi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sxryk.cn/Article/details/gt2zplfnkyy.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gt2gczuqyrm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gt2pctuiihf.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2bmubhqas.html

目  录
来源：http://dali.ppjwa.cn/Article/details/gt2skkfecwq.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2hnyqnuqw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gt2fymyrzwf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gt2hfoppdil.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqvzenga.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dashuyun.cn/Article/details/gt2vrrzjorq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gt2ztcqbszt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gt2sxxvtqhj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gt2zktvsmuw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gt2gultznlw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2ignfrfml.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gt2rrildwpo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2aserxhuq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2lpqvcimv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2ncezlnxf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gt2uktkorak.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sxryk.cn/Article/details/gt2eoocwban.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gt2ndyxppnx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.iojbl.cn/Article/details/gt2ybszcpzk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gt2sffkvkfh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gt2vwogqcnk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2ytsigujq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gt2cckehdif.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2kmwcspbq.html

A. 基础语法与类型
来源：http://dali.gzhubu.top/Article/details/gt2ehkxhleg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cltbmlpf.html

[A01] Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyjzneov.html

Py:   print("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gt2wcpcikje.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gt2amqfinwa.html

JS:   console.log("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gt2zseupxmr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gt2hgvmbivq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gt2hehizrfe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gt2cndfhgrz.html

Ruby: puts "Hello, World!"
来源：http://dali.haohaochexian.top/Article/details/gt2qyyfflrt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gt2nrxjjeqe.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcthfiba.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.haohaochexian.top/Article/details/gt2jxgimizq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2ncqdmzqt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.birdmap.top/Article/details/gt2vpitsplm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gt2wckytrgf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2yomsgmqb.html

Go:   name := "Alex"; age := 20
来源：http://dali.yvedp.cn/Article/details/gt2uacbrcty.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gt2wdocvycx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfmslray.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gt2ymqgyotn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgufenzy.top/Article/details/gt2hqjiiidt.html

PHP:  const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2upgdybdl.html

JS:   const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2awtehfml.html

TS:   const PI: number = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2ygmakqxm.html

Java: static final double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2cxdjvyxe.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gt2dbbmsdkt.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gt2btsknkvt.html

C#:   const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebwnpbzt.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2btjdhalp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tianlin.xyz/Article/details/gt2wilvlvbh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.0kj1m.cn/Article/details/gt2qcxnnutc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gt2yhrxwxpv.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gt2tfhgjpbo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigfzy.top/Article/details/gt2lreyfosf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gt2cikqrunk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuxming.cn/Article/details/gt2wpuflhzl.html

C#:   x.GetType().Name; x is int
来源：http://dali.shuidangran.top/Article/details/gt2byryscsh.html

[A05] 整数除法与取模
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbnmkaal.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gt2yyxncmwv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2qeqaicuh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlkngdpl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2mygftodb.html

Java: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2dfpfijvl.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2trupgylr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2wlizyoqy.html

C#:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2eioemaon.html

[A06] 字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2esbqtlrz.html

Py:   int("42"); float("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2giinonoa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gt2gydnvpdu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sysykeji.top/Article/details/gt2iehqlbib.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gt2vuzhahhc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2gghrnvvy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2wrldabfh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.birdmap.top/Article/details/gt2rkphvgnv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gt2idytpgft.html

[A07] 数字转字符串
来源：http://dali.wangdashe.top/Article/details/gt2effkzlaw.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gt2jfpgeeex.html

PHP:  (string) 42; strval(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2rofhtdby.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gt2zsrywaki.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2eqjpqymw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.iojbl.cn/Article/details/gt2fflnbbvc.html

Go:   strconv.Itoa(42)
来源：http://dali.cheryme.top/Article/details/gt2clgyiinz.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gt2qwjctmov.html

C#:   42.ToString()
来源：http://dali.yuanzhike.top/Article/details/gt2ajxfskuq.html

[A08] 取整与四舍五入
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewxnpozu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbmppvth.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwusfkln.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2rpcpcjag.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.bjfxy.top/Article/details/gt2hgnkpkzf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2qikttzcg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2pduxqxde.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuanzx.com/Article/details/gt2pxnjkonu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2nexegeev.html

[A09] 绝对值与最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2exqlrunc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2gelyieba.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2aosmkzon.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2eztjrmru.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2caksflvj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2cpcxwpvx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gotoacloud.top/Article/details/gt2newspdwv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.andypj.xyz/Article/details/gt2lhnfczqx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2ukcwzqlo.html

[A10] 生成随机数
来源：http://dali.hfpthk.cn/Article/details/gt2gqbfpimq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuxming.cn/Article/details/gt2kbhawzwk.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdrjkuhz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gt2tgtmhaub.html


<!-- 参考信息 -->