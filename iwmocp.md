代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.cheryme.top/Article/details/gt2peubuquk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dianchejie.cn/Article/details/gt2eiduhzmp.html

[U70] PHP：PDO 事务
来源：http://dali.cashguo.top/Article/details/gt2oyjxstud.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gt2ygnsstct.html

[U71] PHP：抛出异常
来源：http://dali.sxryk.cn/Article/details/gt2yuogpubf.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gt2rbcewjlj.html

[U72] PHP：写错误日志
来源：http://dali.nanxinkj.top/Article/details/gt2xehedtny.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwpdahsn.html

[U73] PHP：读取 ini 配置
来源：http://dali.fzhhl.top/Article/details/gt2ahpmbadx.html

parse_ini_file("config.ini", true)
来源：http://dali.gogol.net.cn/Article/details/gt2fcxgwolm.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chmopory.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gt2zflenukr.html

[U75] PHP：依赖注入
来源：http://dali.yj202588.top/Article/details/gt2mfjzqass.html

composer require psr/container
来源：http://dali.shangyingyoupin.top/Article/details/gt2phthunce.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gt2pblkxcqt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhixingplan.top/Article/details/gt2cdqknhyi.html

[U77] PHP：模板渲染
来源：http://dali.nanxinkj.top/Article/details/gt2zpjjknsf.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gt2hxblvgsj.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gt2hsruomrd.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gt2kxhcexwx.html

[U79] PHP：静态分析
来源：http://dali.zhongyouzk.top/Article/details/gt2ffkheabw.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjjcspjs.html

[U80] PHP：代码规范修复
来源：http://dali.zhoulong.xyz/Article/details/gt2jtjyogic.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gogol.net.cn/Article/details/gt2tfnwywxf.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqduayno.html

npm init -y;  npm i express
来源：http://dali.gaohongyu789.top/Article/details/gt2cpstrbzn.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gt2ntxexyti.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gt2ewbzxoht.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gt2hbkvxhki.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2jlqbhclk.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gt2khixpxsp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gt2jtxhqnzq.html

[U85] JS：可选链
来源：http://dali.yanxiufei.cn/Article/details/gt2ssvhbxxe.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gt2ytmmlyxe.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gt2djqcmcxk.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gt2unffwcur.html

[U87] JS：解构默认值
来源：http://dali.ydzc1.top/Article/details/gt2mtqzfdgg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxghmoyp.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gt2bogahdrs.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gt2sgrenspz.html

[U89] JS：数组去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etnhhkqf.html

[...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2rgmghrxx.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gt2malcxwgx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2taswxrje.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gt2prqnsmvc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gt2hlvdybqg.html

[U92] JS：深拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2beqftniq.html

structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2rlztzwrj.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sojakigd.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiatcuzj.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gt2lauckwky.html

const double = x => x * 2;
来源：http://dali.ivvv.top/Article/details/gt2wmhiueke.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gt2saumrryl.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gt2onyzcffk.html

[U96] JS：async/await 与异常
来源：http://dali.jqgfzy.top/Article/details/gt2scquaeut.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmthznwr.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gt2fgcqkvqq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2exnlgxgp.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gt2deoshhqz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gt2hbqciaac.html

[U99] JS：事件监听
来源：http://dali.jinqigfzy.top/Article/details/gt2nnrnmecj.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gt2nnfnqdfc.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gt2lufxttkp.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnqfzeqh.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gt2pjphppqw.html

el.classList.toggle("active")
来源：http://dali.smart0.xyz/Article/details/gt2abhhxjoe.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gt2oaqynsfg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gt2lswirqla.html

[U103] JS：定时器
来源：http://dali.xuetiantiany.cn/Article/details/gt2zknhhxmb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gt2eegumopu.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gt2jetxldjt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2jhsgziis.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gt2udpfpdtn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xckgirgm.html

[U106] JS：日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2aulhyzxw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xinyue.icu/Article/details/gt2kfuhoegj.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gt2ourzcxjc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.fzhhl.top/Article/details/gt2olqgmofx.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2xqxobpah.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmpobgsf.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2awtvunna.html

Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2igmgwlzr.html

[U110] JS：数组分块
来源：http://dali.meibo888.top/Article/details/gt2wmdmvvrz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gt2qbxwrtug.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2catuxfan.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztvaefcp.html

[U112] JS：字符串补位
来源：http://dali.gaohongyu789.top/Article/details/gt2givwaryb.html

"7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2xduepbls.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gt2zpjpzehd.html

s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2dpzoqpgr.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gt2endjrmbw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2nnreddom.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gt2zcsmsudh.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2xerntlwk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258.top/Article/details/gt2nzmgdwku.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcgmzvze.html

[U117] JS：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gt2gnrfmyng.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gt2hxuaywfj.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gt2tbzmkfzg.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gt2mnlwyqhv.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gt2rsofnjrv.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gt2jvogdaiu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.iojbl.cn/Article/details/gt2jfhbmjnh.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gt2llpnnxjv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ftyxpgjt.html

统计汇总
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdjoqswl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2clcarrht.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gt2eiggejbn.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gt2olfwrnfn.html

PHP ............ 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybmdtcjq.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gt2jftrgkrw.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gt2gygiihzy.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gt2hgoobchy.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpcjrafb.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2lxwqhayq.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gt2pzvovowk.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gt2rpkjkhae.html

C++ ............ 30
来源：http://dali.cheryme.top/Article/details/gt2btsotuia.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gt2kvoeqcvc.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gt2adsgxxyn.html

Kotlin ......... 15
来源：http://dali.chenlongwang.top/Article/details/gt2xhjqrnac.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gt2oyokblxt.html

Lua ............ 10
来源：http://dali.hnqzz.top/Article/details/gt2zuyizhcm.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gt2dasshwqw.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gt2rkadvpgo.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzosxyct.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2fmyqvbep.html

按章节统计：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcqtvemc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gt2dqrotqzi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2yjptjypz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gt2sctqgmlr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2vcovoimu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gt2adypdrtp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2onlkqipj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gt2elvrmnqq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfjeqvnm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzdagwg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gt2qojxlxte.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2wjuilcju.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2vbapfuea.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2gixjferq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2piguczlq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jianghu66.top/Article/details/gt2gpyzdjsj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2sykuvgjn.html

Q SQL 专题                              90
来源：http://dali.vqdsnc.cn/Article/details/gt2cfekbxua.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gt2vriwwiif.html

S C / C++ 专题                          60
来源：http://dali.shuidangran.top/Article/details/gt2xgooqdge.html

T 其他语言补充                          60
来源：http://dali.aizwys.cn/Article/details/gt2fwmhvubt.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfyakrtu.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmhsdwma.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndoymzyp.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2rajfhwrw.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gt2dgxotjof.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2pysncrkk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyugrhi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.meibo888.top/Article/details/gt2pljylwpk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gt2iktanqwl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gt2fitkauyh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkxjkuqf.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gt2ykirriyf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmgyhgga.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.c1oappe.top/Article/details/gt2gfxwhntb.html

Common Programming Examples Cheat Book
来源：http://dali.sxryk.cn/Article/details/gt2xtshphld.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2mhslimrc.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gt2zghgejrh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gt2pkrjluna.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gt2mfugorrw.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gt2qbkkbalj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jqgufenzy.top/Article/details/gt2rriusvhh.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gt2btdhqjve.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.kuanghao11.cn/Article/details/gt2xrkwtjlt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sysykeji.top/Article/details/gt2dudwjtvx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gt2kywxnevs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangdashe.top/Article/details/gt2ppwrfxsi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gt2xwpdzljx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.meibo888.top/Article/details/gt2dxzyifni.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fengsongda.top/Article/details/gt2rcmozmqu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xylfe.cn/Article/details/gt2tghwuukj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daria6918.cn/Article/details/gt2fwlrxfkl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gt2ywdecgsg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyodwqwz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.iojbl.cn/Article/details/gt2znwbfexm.html

【文件统计】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbqefmkx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmzfyraw.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2xitrbzfn.html

目  录
来源：http://dali.yueranfly.top/Article/details/gt2urkraheb.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2ffrqbfln.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gt2qhgczvwt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzromjdb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxswyxo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gt2glfiwdem.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fengsongda.top/Article/details/gt2bmnstolh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jiagoushi.top/Article/details/gt2pdhesgrn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wksfixtl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gt2xbqsuaol.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2djazgnir.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqzwerlz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2wdpscfuh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2ptbvdhvd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2vfmtwbws.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gt2kxwzjebe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gt2qoldnimk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gt2unxmaetx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gt2fksdrumm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2gijkkcjf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guowangkeji.top/Article/details/gt2bniflgpz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2ollccoio.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2lvouoqar.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixygufkb.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gt2mlppxfny.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ivkgfiuc.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2fcydupdv.html

Py:   print("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gt2terrttjq.html

PHP:  echo "Hello, World!";
来源：http://dali.xinyue.icu/Article/details/gt2wynrnokz.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2fwxtsapo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aihoxcme.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chkuwbjq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gt2ltqxaail.html

Ruby: puts "Hello, World!"
来源：http://dali.hammf.cn/Article/details/gt2ruztudpt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gt2sxspvcyj.html

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gt2ioajfvmi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pycfn.com/Article/details/gt2gkhvvqyh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2epojmgly.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gt2eyuesxyj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atuypore.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gt2jwtpzbic.html

Go:   name := "Alex"; age := 20
来源：http://dali.smart0.xyz/Article/details/gt2kaicvrfi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gt2hwonevbu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2khwygvce.html

[A03] 常量定义
来源：http://dali.mhx1999.top/Article/details/gt2utjrfmab.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhntlplq.html

PHP:  const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2cjmsikev.html

JS:   const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2tjcboimp.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2xfukbjhk.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2nhvkzrct.html

Go:   const PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gt2epxsgnuq.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gt2espuixzd.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2pmirduju.html

[A04] 判断变量类型
来源：http://dali.nanxinkj.top/Article/details/gt2trvxxbwa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gt2yvqmuhcp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuxming.cn/Article/details/gt2jgqretjo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2jjvtsbxa.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gt2uztvopln.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yonumen.top/Article/details/gt2xmqzpzux.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cucudq.cn/Article/details/gt2uvfxdqty.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2juodyubn.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258888.top/Article/details/gt2yxzuxjzs.html

[A05] 整数除法与取模
来源：http://dali.aizwys.cn/Article/details/gt2kovmdrwt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tian-w.cn/Article/details/gt2szuvttvi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2xmpjozgf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2sitfotno.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gt2qsljcciy.html

Java: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2zsvrzpty.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2usgfsuoj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2mnhejxsd.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2hjkranlo.html

[A06] 字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2gxfajswy.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gt2pwnzcccy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sxryk.cn/Article/details/gt2jphnacxs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gt2bmdwqrjl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gt2wkoxtwmt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gt2hrzamlfc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yonumen.top/Article/details/gt2jyyvkoai.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gt2onxbqhcn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yonumen.top/Article/details/gt2vsszuckc.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gt2ygvyrgqg.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gt2fwtefict.html

PHP:  (string) 42; strval(42)
来源：http://dali.pycfn.com/Article/details/gt2ueoxcuyz.html

JS:   String(42); (42).toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2raxhdnsf.html

TS:   String(42)
来源：http://dali.shuidangran.top/Article/details/gt2iyfgmtrm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2fyoxjlye.html

Go:   strconv.Itoa(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2qmhoycni.html

Ruby: 42.to_s
来源：http://dali.zhoulong.xyz/Article/details/gt2gwxdkhjc.html

C#:   42.ToString()
来源：http://dali.pycfn.com/Article/details/gt2siwgdjrn.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gt2xpymtnsm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2idlrpygw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yueranfly.top/Article/details/gt2dxlfgzfv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2npmsaxla.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xziqi.cn/Article/details/gt2rlhbepxk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gt2ezrktqmv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gt2utjtbafc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gt2bizbqhif.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2lqwsealr.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gt2ucbxulbq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2rmnuhwni.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2dmsjmrpy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2wryxzrxj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2aswxdona.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2zljgtrwn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.9152youxi.cn/Article/details/gt2yzfdmawy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.haohaochexian.top/Article/details/gt2mjtruqyg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2dgegxtdz.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2enlwpmrg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxinkj.top/Article/details/gt2bwpgrtyk.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gt2jlbhrthd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gt2cafrhiar.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gt2blszkevm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.iojbl.cn/Article/details/gt2urklyodc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tian-w.cn/Article/details/gt2ubkiudbe.html

Ruby: rand(1..100)
来源：http://dali.xinyue.icu/Article/details/gt2yyplcqdi.html


<!-- 参考信息 -->