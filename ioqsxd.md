代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtikrytujk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.316326.xyz/Article/details/gtsffyfqba.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gtpkxfeanj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gtvnlgnsmk.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprkoygdb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gthaeehvid.html

[U70] PHP：PDO 事务
来源：http://dali.316326.xyz/Article/details/gtnglhrjda.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.redwolf501.top/Article/details/gtafleqdbq.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtgsksnlsr.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gthxiaztwa.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gtyooiinwb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gtwzbozpyb.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gtxzujgwik.html

parse_ini_file("config.ini", true)
来源：http://dali.dianchejie.cn/Article/details/gtpyntnzdo.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtiraticiy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cucudq.cn/Article/details/gtbwltcncc.html

[U75] PHP：依赖注入
来源：http://dali.dashuyun.cn/Article/details/gtauqocsxi.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtggljxghv.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gtglukqnns.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenlongwang.top/Article/details/gtxxenjhzv.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gtwpmpktxa.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujaoxhjr.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtwcqqhqww.html

composer require --dev phpunit/phpunit
来源：http://dali.mhx1999.top/Article/details/gthheqflwk.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gtdkhtytwt.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtmnoloqvg.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gtpfllliby.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtkzjuquzy.html

[U81] JS：初始化项目
来源：http://dali.xuanzx.com/Article/details/gtzrzacojd.html

npm init -y;  npm i express
来源：http://dali.c1oappe.top/Article/details/gtzznbbcts.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gtjaottxtt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.0kj1m.cn/Article/details/gtbkjjitam.html

[U83] JS：ES Module 导入导出
来源：http://dali.316326.xyz/Article/details/gtjbimlweu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtjppfgsvz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtayxtocqh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gtwvkmxjvi.html

[U85] JS：可选链
来源：http://dali.yuanzhike.top/Article/details/gtpvsdyyta.html

a?.b?.c
来源：http://dali.jinqigfzy.top/Article/details/gtwompkkxt.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gtdedkytny.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gtbphwnfel.html

[U87] JS：解构默认值
来源：http://dali.xziqi.cn/Article/details/gtomvcfubg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258888.top/Article/details/gtcyjrtujd.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gtkvabcvuh.html

{ ...a, ...b }
来源：http://dali.xuetiantiany.cn/Article/details/gtsndefxjl.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqxgukyt.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtohujonde.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gtuvhmhyuj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtaiwyycwm.html

[U91] JS：对象键值遍历
来源：http://dali.kuanghao11.cn/Article/details/gtchixoxis.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gtytywbrzp.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gthhlvaqfa.html

structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtpejvdvye.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gtpsxypkzm.html

`共 ${n} 条`
来源：http://dali.c1oappe.top/Article/details/gtrhwdcken.html

[U94] JS：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtfqngfjhi.html

const double = x => x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtnqkdakyu.html

[U95] JS：Promise 包装
来源：http://dali.zhixingplan.top/Article/details/gtirnkckjg.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtnqrebunk.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gtvyrywoja.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtzkptuomm.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvmduezr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtzycckuwp.html

[U98] JS：fetch 带 JSON
来源：http://dali.daria6918.cn/Article/details/gtxhcznjdh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gtxctjtuns.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gtxqeevoig.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gtqxlablhj.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gtcledqjnz.html

document.querySelector(".item")
来源：http://dali.nanxinkj.top/Article/details/gtvqryvisp.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtgcpsobze.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtrebixfxg.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gtxunerfvg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiilerua.html

[U103] JS：定时器
来源：http://dali.sxryk.cn/Article/details/gtbtoygnme.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gtnnitylmp.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gtwxwvwjnm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtutuasmbb.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtvpygzisx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtdyhymvzq.html

[U106] JS：日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwxilsyk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gtewynxexe.html

[U107] JS：数字千分位
来源：http://dali.nwbrower.top/Article/details/gtjngthvsx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gtyjmkukxo.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gtmkaznskm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtriftthqr.html

[U109] JS：数组分组
来源：http://dali.hongshengwenyu.top/Article/details/gtmcqnvgpi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtmwkzkbad.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gttxrjwvqw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gtpumdmsyd.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gtkuptkafg.html

new Map(Object.entries(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtckvnmqeb.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gtgenixgon.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtlyklbktq.html

[U113] JS：正则替换全部
来源：http://dali.pengpengdd.cyou/Article/details/gtlzdyczcp.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtnofpvpal.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gtijcsbucs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtfcenkyyv.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gthaicakvo.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjmlrigu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gtgvbweyty.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfjxrdbty.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gtmyodzfal.html

npm i -D vitest;  npx vitest
来源：http://dali.yonumen.top/Article/details/gtlgiojfll.html

[U118] JS：开发服务器
来源：http://dali.hysaishi.cn/Article/details/gtbpdluylo.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtfytogdfn.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gtjulyhbnu.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gtczapocdj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shangyingyoupin.top/Article/details/gtilkyvvco.html

import.meta.env.VITE_API_URL
来源：http://dali.chenlongwang.top/Article/details/gtlttqdyvn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthjrpbcbp.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfbzwwdt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsbzzhezs.html

按语言统计（条）：
来源：http://dali.wangdashe.top/Article/details/gtbhnyodwc.html

Python ......... 252
来源：http://dali.dashuyun.cn/Article/details/gtktahothf.html

PHP ............ 252
来源：http://dali.hongshengwenyu.top/Article/details/gtlypgapvg.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gtvsexjwho.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gtqfsqvzhu.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtylbaaccf.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gtdjdxgszo.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gtmkxculhp.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtdggbpxsh.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtgkilxywy.html

C++ ............ 30
来源：http://dali.daxiang520.top/Article/details/gtxxktfkcx.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtcenubbov.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtyoqpwvaj.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gtcwlhdkli.html

Swift .......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtwoaovsuf.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gthznkclvb.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gtttiwdtzs.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gtwgmsedzo.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtvlhwibft.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gtzzkdrdhl.html

按章节统计：
来源：http://dali.pengpengdd.cyou/Article/details/gtvgymhcjt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiymlurt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylloidhx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtujgposvd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gttegfznsi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gttfytbawz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtmfffjlxf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgaxtxwf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwvwehsd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfjuyckq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtrskzgrpv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaflbunj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtbkdegkyv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtskayapvm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtfzwcxtpw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hywenlv.cn/Article/details/gtnjlozogu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtzpayxzjv.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmyegvkf.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gthmwcmmip.html

S C / C++ 专题                          60
来源：http://dali.zhongyouzk.top/Article/details/gthpbitjsd.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gtuatwxnvj.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gtmmrtmwko.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gthmpbwkag.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtyjgwhrba.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtulxdjpqz.html

使用提醒
来源：http://dali.bjfxy.top/Article/details/gtlubihkpn.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gthdnqsokg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zdqjudy.top/Article/details/gtblsgiobm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gthncavubu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtfpkjhxwy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrpuumkt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gtmibuoyta.html

—— 文件结束 ——
来源：http://dali.svipenyu.cn/Article/details/gtehiskbfm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthdvdeeki.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuetiantiany.cn/Article/details/gtwpubqrre.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gtriehbdmo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyhoknzfi.html

【收录内容】
来源：http://dali.hnxiangtu.top/Article/details/gthzruuqzu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.haohaochexian.top/Article/details/gtnsvvwlut.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhixingplan.top/Article/details/gtapzitcwb.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddybphor.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258.top/Article/details/gtaybioefl.html

【使用说明】
来源：http://dali.yonumen.top/Article/details/gtmaueyxrm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xinyue.icu/Article/details/gtpcbfxexv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gtyuriqojs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhiwuduotai.top/Article/details/gtohhacbrh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.316326.xyz/Article/details/gtoaloifvx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuanzx.com/Article/details/gtashhxkki.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xinyue.icu/Article/details/gtwxhkpbyh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sxryk.cn/Article/details/gtoqzxsqym.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.0kj1m.cn/Article/details/gtzftrpzjy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.snrcjt.cn/Article/details/gthnliroko.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xziqi.cn/Article/details/gtdwobhgac.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cashguo.top/Article/details/gtatbuygty.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenzaomai.com/Article/details/gtknxuzhlr.html

【文件统计】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupkbfjmy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuanzx.com/Article/details/gtepaowmue.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtmxuormhz.html

目  录
来源：http://dali.c1oappe.top/Article/details/gtsucwvdad.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtgvwqvule.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtfphuxdfp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtcpwdcewc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtrldeveuj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtygouhswq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtwweefg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gtprxxqnfs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtyyintgiq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtfhjwkszo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gttupqnxwo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtdppepwxw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gthkuoxwfl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtyplnumui.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gttnrsbmhe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gtnoztncbo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgfzy.top/Article/details/gtiocquwcz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtouibpfta.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgfzy.top/Article/details/gtfmqocaxq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yonumen.top/Article/details/gthgcslauu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtbqiepgfw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtbjbvdgsg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtuvfkypvg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnnqzabey.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gtehmljovl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqmdthnxl.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtaumtpugv.html

Py:   print("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gtmwmiyutx.html

PHP:  echo "Hello, World!";
来源：http://dali.mhx1999.top/Article/details/gteoslxjzv.html

JS:   console.log("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtwogthtaz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zdqjudy.top/Article/details/gtzuiwqivr.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gtrbzkitye.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtsvpzlmvi.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gtjqcahrcw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtqrdaedis.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgytogmyo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.svipenyu.cn/Article/details/gtnklvblzw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtxawhiebj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtswkmvsqm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtnkjybrqm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtvjuscsnz.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gtlzykwbws.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gtgufgccde.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gttcyhnlrq.html

[A03] 常量定义
来源：http://dali.cashguo.top/Article/details/gthaswloyd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.kuanghao11.cn/Article/details/gtrosfmcjv.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtmdhmyilm.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtyojbiljj.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtdydwtaae.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtjyqadjuk.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtcbnqdjzu.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtguchbucx.html

C#:   const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtkhjyrtbr.html

[A04] 判断变量类型
来源：http://dali.xinyue.icu/Article/details/gteazjnkmi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gtwnsdpbnf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jianghu66.top/Article/details/gtbksjfmqx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gtaczsqjvw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gtjmofrdpw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tian-w.cn/Article/details/gtosolsmad.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangtech.top/Article/details/gtarradmbk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuxming.cn/Article/details/gtkglwwhnd.html

C#:   x.GetType().Name; x is int
来源：http://dali.cheryme.top/Article/details/gtsawlfjfo.html

[A05] 整数除法与取模
来源：http://dali.fengsongda.top/Article/details/gtogdeffyp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.andypj.xyz/Article/details/gtsmcmovao.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtecxeckfa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtlctgizfj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtjltxcvyt.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtluuyhrgh.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtczykqwrg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtejuerkfw.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtngiavxtm.html

[A06] 字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtjiylfrah.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gtgecdjptv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gtgbqhjcno.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.bjfxy.top/Article/details/gtpfikumti.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtmbmwlryt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtpytyedke.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.quarkkingdee.top/Article/details/gtpimifzly.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.havefunace.top/Article/details/gtslingwha.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pycfn.com/Article/details/gtrkujqptc.html

[A07] 数字转字符串
来源：http://dali.chenlongwang.top/Article/details/gtqbrkcqob.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gtaezbzezd.html

PHP:  (string) 42; strval(42)
来源：http://dali.quarkkingdee.top/Article/details/gtoevtuysq.html

JS:   String(42); (42).toString()
来源：http://dali.smart0.xyz/Article/details/gtiepwufyh.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gtftyuzpbn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gttojsvssa.html

Go:   strconv.Itoa(42)
来源：http://dali.sufxvd.cn/Article/details/gtpgmtgtvy.html

Ruby: 42.to_s
来源：http://dali.xuanzx.com/Article/details/gtrcjwgqdd.html

C#:   42.ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtkfzlssdm.html

[A08] 取整与四舍五入
来源：http://dali.shzxlz.cn/Article/details/gtsjniiiag.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtlakbaqxt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyredykae.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtsmvoydfk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gzhubu.top/Article/details/gtjetvwtls.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplpjulln.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtrektenmg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yangfankeji.com/Article/details/gtlhsbznxs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtnmdxuzou.html

[A09] 绝对值与最大最小值
来源：http://dali.sweek.top/Article/details/gtnefowbzn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtwfqecmmc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtazrtrkeu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtomslshcy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gttmjqbben.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthfmnmsts.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tianlin.xyz/Article/details/gtlhsddtll.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gzhubu.top/Article/details/gtjjbalfij.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtjkcswbmq.html

[A10] 生成随机数
来源：http://dali.cdnleiting.top/Article/details/gtehedlwwf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gtftnvvxvs.html

PHP:  random_int(1, 100);
来源：http://dali.daria6918.cn/Article/details/gtizgvzeib.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtxyeprxvu.html


<!-- 参考信息 -->