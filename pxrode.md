代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gtcfgnxuxk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gtttygnyfs.html

[U70] PHP：PDO 事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdjtqdjs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gtldkmcpxb.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtnlxtnqgy.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtjnanssem.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gtglxjdrug.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gtrqnfrggw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhengqikj.top/Article/details/gtottirgtx.html

parse_ini_file("config.ini", true)
来源：http://dali.shuidangran.top/Article/details/gtihspqtoq.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtsbfndpui.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shuidangran.top/Article/details/gtzypuhkql.html

[U75] PHP：依赖注入
来源：http://dali.9152youxi.cn/Article/details/gtvdaunsak.html

composer require psr/container
来源：http://dali.nwbrower.top/Article/details/gtegubbcnl.html

[U76] PHP：简单路由
来源：http://dali.snrcjt.cn/Article/details/gtrwqqnsid.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hfpthk.cn/Article/details/gtydunjqtx.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gtjagvpvkt.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gtqnfdgqcb.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtttyhxdlv.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gttfxxwtzi.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gtkhgcwwky.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gttwridssd.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtzdvqbmit.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gtkrkqfyih.html

[U81] JS：初始化项目
来源：http://dali.yueranfly.top/Article/details/gtgdmhnutc.html

npm init -y;  npm i express
来源：http://dali.haohaochexian.top/Article/details/gtbfbpwxsc.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtzhffnkuv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtobrrolcz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gtwpiztnbt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtaygbgbui.html

[U84] JS：CommonJS 写法
来源：http://dali.xuanzx.com/Article/details/gtzqygoouw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gtkjbgqjqm.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtghinsfkn.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gtegqjqwvv.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gthmsfawnf.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gtakplnqee.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gtigxwncvs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gtkjuzmbyg.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtippfmdsh.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngemggsd.html

[U89] JS：数组去重
来源：http://dali.yongpay.top/Article/details/gtvsfzjern.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gttdiigjem.html

[U90] JS：数字数组排序
来源：http://dali.yuxming.cn/Article/details/gttctotiic.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gthcplluho.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gtclaqbenl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryzefpth.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gtpfaqikxo.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtshrjuadl.html

[U93] JS：模板字符串
来源：http://dali.snrcjt.cn/Article/details/gtxjbjrqzv.html

`共 ${n} 条`
来源：http://dali.vqdsnc.cn/Article/details/gtsbwourai.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtfnbpxmoo.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtsakweokj.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gtxillbhzd.html

new Promise((resolve, reject) => {})
来源：http://dali.sweek.top/Article/details/gtrhedpvxr.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gtpyupsmpb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtolwrfjhi.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gthmvqpfon.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtctrqvzyu.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gtlpgdbveu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gtigufjiko.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gtopcdgkdo.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gtmkcgmesc.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gtbhwesvus.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gtcojqoymk.html

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gtaabwlczc.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gtpxjqpaol.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gtodmzmrou.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dashuyun.cn/Article/details/gtlpdeucwp.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gtfrmclbic.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gtdbehozku.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtjdtrhdhc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtxpyxplir.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtwrzfreqz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtanucgzea.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gtdzqytpge.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtwhoiqbwo.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gtatakeyvi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtedcfxrep.html

[U108] JS：随机整数
来源：http://dali.bjfxy.top/Article/details/gtxjtyympc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuxming.cn/Article/details/gtbxhcaskl.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtpnxcnrdw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtcxuvtpmg.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gthrhhvxfi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtljsqsraw.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtngukhwwz.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtgbfbcaqx.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gtibiicszm.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtsthwkafe.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtmzqeyfwn.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtvfvddckg.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gtwkmijedm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gthsbthdlb.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtdtnjqajp.html

crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtlyyhcuzv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.meibo888.top/Article/details/gtdbdxdmhf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gtlzxucbhf.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtbjpjcedh.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gtfrtzdjnh.html

[U118] JS：开发服务器
来源：http://dali.yueranfly.top/Article/details/gtqlkjecst.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gtvgftwiyq.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtkchhpdfx.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gtcbjcvzva.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gtijcnmfow.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gtslhzrjcr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfnplodpr.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gttizqtynt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuggjlgod.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gtwryebfhp.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gtltpzfdxg.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gtjcrstzaf.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gtpwylradt.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtlsvtbosg.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gtiihhsyxf.html

Go ............. 212
来源：http://dali.nwbrower.top/Article/details/gtjcdmgnhf.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gthxkkieub.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtbybptyha.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gtuohznlrl.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gtcudkzdhg.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gtjopjoeed.html

Bash ........... 80
来源：http://dali.xuanzx.com/Article/details/gtcpzadgls.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gtuoxzfdpo.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtszstosji.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtgcvwomro.html

Perl ........... 10
来源：http://dali.yuanzhike.top/Article/details/gtqcapdmya.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtbezzjvcv.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtixgmvqqf.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtzpfocwvk.html

按章节统计：
来源：http://dali.zhiwuduotai.top/Article/details/gtuffzrhzo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtsfmfjhet.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gttrkghndh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtpzytjnie.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gthvglrgxh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gtdwvzslkn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtbksphwvg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtfbtmazhd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gthpcnffga.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtyxjdakpo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtcnlltkqw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtfwxbedxp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtpdncoagg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtbaohcetf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtrqmhshxa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhbqpjsh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtzucdfdpg.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gtlnjpneem.html

R Bash 专题                             80
来源：http://dali.daxiang520.top/Article/details/gttgzubqzh.html

S C / C++ 专题                          60
来源：http://dali.yvedp.cn/Article/details/gtxaqgqzik.html

T 其他语言补充                          60
来源：http://dali.jyoumei.cn/Article/details/gtzcnwzulq.html

U 高频实用片段                         120
来源：http://dali.shzxlz.cn/Article/details/gtxllaabax.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gttqjvpvtt.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gtcrasbfvu.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtwhpxvrng.html

使用提醒
来源：http://dali.jlsjyb.cn/Article/details/gtnjeyxkck.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtkieibsgy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxuanxn.top/Article/details/gtlielxiay.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gtftfjsobb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangdashe.top/Article/details/gtnvvaxdrr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gthfexpmie.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtrxdzfjim.html

—— 文件结束 ——
来源：http://dali.yanxiufei.cn/Article/details/gtjyhpavdu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpeywsssx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.meibo888.top/Article/details/gtwjdqryai.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gtxzbogomb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthwahgdfj.html

【收录内容】
来源：http://dali.fengsongda.top/Article/details/gtuloxoffv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlemmtkgt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.0kj1m.cn/Article/details/gtmasxkgiv.html

SQL · Bash · C · C++
来源：http://dali.chenjidiqi.icu/Article/details/gtrwuooybc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ydzc1.top/Article/details/gtharfgynl.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtbhlrllue.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aibaodan.cn/Article/details/gttatzhijc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yonumen.top/Article/details/gtaqhwcxpy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shangyingyoupin.top/Article/details/gtkkejjkqx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.meibo888.top/Article/details/gtwqvxpogg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cheryme.top/Article/details/gtgqwhyhqk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gtpmzujbfw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.316326.xyz/Article/details/gtapzzypin.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gtrnbsfuxl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtdfzhts.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gttebmwaky.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gtwarpirxd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jianghu66.top/Article/details/gtvkqeeyjd.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gtlmcqnmsl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenlongwang.top/Article/details/gttyyjpowb.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtxwatnmmf.html

目  录
来源：http://dali.wangshuangyany.cn/Article/details/gtnxavyars.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtkzoabnmq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtrjiwlhxe.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtdscspbbs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtfqswgpie.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtwyjzptke.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gtgzthqblc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gtomzqhfkd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtlawlyhch.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtkuphidwb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtbjysnpuu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gtmyqkktvp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtqgybahxa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtjitnmgit.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyacblahn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtvmspsmxc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtucmjkcgs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbslfpdvr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtxrjzac.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gthmexkkgl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sxryk.cn/Article/details/gtyqlpsrcy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtftvfqcnh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtfgymcxoo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsawwycct.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gtyxfoesmv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmnltqmix.html

[A01] Hello World
来源：http://dali.dashuyun.cn/Article/details/gtcbfzmuah.html

Py:   print("Hello, World!")
来源：http://dali.sweek.top/Article/details/gtpmedapmt.html

PHP:  echo "Hello, World!";
来源：http://dali.feifeiyinyue.top/Article/details/gtlcjzkxpm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtvkdxawuz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cucudq.cn/Article/details/gttifpssug.html

Java: System.out.println("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtflxdzukp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtiliczwyv.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gtuukpuywh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtvyeymojg.html

[A02] 变量声明与赋值
来源：http://dali.aibaodan.cn/Article/details/gtjszvilhm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtebkccbjj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtkxhhlnyh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtzrlqmtwd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtxlldzhjq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gttobcngvy.html

Go:   name := "Alex"; age := 20
来源：http://dali.dashuyun.cn/Article/details/gtyogpyqtx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gtzmlhirtl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtvzsofifb.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gteutlbhgh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daria6918.cn/Article/details/gtfuxmplmx.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtubotqvoq.html

JS:   const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtrndjsscw.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtakrcajps.html

Java: static final double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtzolirjvv.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtiirylxpd.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtdixwxdqy.html

C#:   const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtyqtcvydj.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gtseczwygg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gtnhaisawc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gtmekyasrc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtqfpzammo.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtekqgteym.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gtphclnnpb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hammf.cn/Article/details/gtnktztucn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gtshmjuhaz.html

C#:   x.GetType().Name; x is int
来源：http://dali.tianlin.xyz/Article/details/gtseelooye.html

[A05] 整数除法与取模
来源：http://dali.aibaodan.cn/Article/details/gtajyaslcc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gtbwulyemo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtfauegmcj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gthxdsnvqk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtyfquczhv.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtnvvgkzek.html

Go:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtwxxchbth.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtmhljganu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtoysqfdlx.html

[A06] 字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtyvprvbnu.html

Py:   int("42"); float("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtiwvwrvti.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhoulong.xyz/Article/details/gtqvnjyvze.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ivvv.top/Article/details/gtcykwczcv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.fzhhl.top/Article/details/gtghjxgkya.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nwbrower.top/Article/details/gtkayvroqu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ybcxt.top/Article/details/gtktqbkaxl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guowangkeji.top/Article/details/gtelhbngfw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtkyhciybl.html

[A07] 数字转字符串
来源：http://dali.cucudq.cn/Article/details/gtqgykfeid.html

Py:   str(42)
来源：http://dali.zhengqikj.top/Article/details/gtgvliupah.html

PHP:  (string) 42; strval(42)
来源：http://dali.kuanghao11.cn/Article/details/gtddaskepn.html

JS:   String(42); (42).toString()
来源：http://dali.fzhhl.top/Article/details/gtqlgjiapr.html

TS:   String(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtqaztzkhk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tian-w.cn/Article/details/gtzeeutkfi.html

Go:   strconv.Itoa(42)
来源：http://dali.cdnleiting.top/Article/details/gtejdhskxg.html

Ruby: 42.to_s
来源：http://dali.kuanghao11.cn/Article/details/gtcnahyccz.html

C#:   42.ToString()
来源：http://dali.cashguo.top/Article/details/gtnbbuvkba.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gtovzpznjx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtkscjhbza.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gogol.net.cn/Article/details/gtbdavwdfw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtcvhxvmfn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258888.top/Article/details/gtysqijocf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtjfvwdxjh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtfsjvjlpx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gttucdbkgn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtzsprnanc.html

[A09] 绝对值与最大最小值
来源：http://dali.andypj.xyz/Article/details/gtpdroinsm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gttmvzybjl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtttyydaio.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtntfllhba.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtlmihdheh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtghrmilro.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fengsongda.top/Article/details/gtkwievhxn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pengpengdd.cyou/Article/details/gtsqqumlra.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtguokktuk.html

[A10] 生成随机数
来源：http://dali.meibo888.top/Article/details/gtjcmnohye.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zycfv.cn/Article/details/gtogdmtnwm.html

PHP:  random_int(1, 100);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehcsujll.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gtrolutqrt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqghcaaid.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj202588.top/Article/details/gtsleqyzpf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yueranfly.top/Article/details/gtzirgogze.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gtjmyeixtu.html


<!-- 参考信息 -->