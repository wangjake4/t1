代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gtrajcobvb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jianghu66.top/Article/details/gtpgwawvde.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigfzy.top/Article/details/gtpewikvug.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxinkj.top/Article/details/gtevyaevrm.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtmqazwqfg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtcxmgkkoe.html

[U72] PHP：写错误日志
来源：http://dali.snrcjt.cn/Article/details/gtllmoequw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtqyirrqij.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gtrdfseain.html

parse_ini_file("config.ini", true)
来源：http://dali.shzxlz.cn/Article/details/gtmzaqxrto.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtwjookahj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gtgfnviehr.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gticadqikb.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gtbuwexinu.html

[U76] PHP：简单路由
来源：http://dali.zhoulong.xyz/Article/details/gtwondnlcp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gtvbjfriqv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gtbpaibnky.html

composer require twig/twig
来源：http://dali.hysaishi.cn/Article/details/gtjsbpmmub.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtkvmuzwpb.html

composer require --dev phpunit/phpunit
来源：http://dali.chenlongwang.top/Article/details/gtquqisafg.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gtvozocaxo.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gtttuvhove.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gtmcbnvpiz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ehwqpu.com/Article/details/gtgfhclnrg.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtqxxgxvuo.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gttvfbesnb.html

[U82] JS：package.json 脚本
来源：http://dali.fengsongda.top/Article/details/gtboyofnka.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangdashe.top/Article/details/gtcxodouza.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gtadlhfywf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtdbeerkuu.html

[U84] JS：CommonJS 写法
来源：http://dali.iojbl.cn/Article/details/gtdplmnkbn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gtbidwfjaq.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gtpxocxyco.html

a?.b?.c
来源：http://dali.zhoulong.xyz/Article/details/gtcjbcxwnf.html

[U86] JS：空值合并
来源：http://dali.yj202588.top/Article/details/gtekqiviqh.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gteznpqtgw.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gthnelrmua.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shzxlz.cn/Article/details/gtxevsyuhs.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gtrcwmatvc.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gthwxfayhi.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gtxzuqkjye.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtsrprrqvb.html

[U90] JS：数字数组排序
来源：http://dali.yuxming.cn/Article/details/gtyexlpxtp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtjfccauve.html

[U91] JS：对象键值遍历
来源：http://dali.meibo888.top/Article/details/gtisdpiwtt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gttdwveptw.html

[U92] JS：深拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtiumdpdgf.html

structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtgkklxfaw.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtjljhydyn.html

`共 ${n} 条`
来源：http://dali.xziqi.cn/Article/details/gtagntgykp.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtiqypqade.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtwrwogaac.html

[U95] JS：Promise 包装
来源：http://dali.xuanzx.com/Article/details/gtpeakrxyr.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgufenzy.top/Article/details/gtomowxiiq.html

[U96] JS：async/await 与异常
来源：http://dali.cucudq.cn/Article/details/gtvziuqhso.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqmqlzos.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtwicvdboj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtvkbtqzeb.html

[U98] JS：fetch 带 JSON
来源：http://dali.0kj1m.cn/Article/details/gtlspptwgk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cashguo.top/Article/details/gtmddinmxr.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gtpkckvkfe.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtjbinpigq.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gthmtupgle.html

document.querySelector(".item")
来源：http://dali.tian-w.cn/Article/details/gthsgyikzn.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gtxcynqnzp.html

el.classList.toggle("active")
来源：http://dali.jinqigufen.top/Article/details/gtwhnkhynn.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtrrkgzugz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gtpzwhhlxa.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gtvyeonovq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gtcpsqalqz.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtdlwqqcvu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtvolvqmku.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgzzpnvp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtflwvrhoe.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtozmrbnmi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gtkxfdreko.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtfvyozkde.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtetulppse.html

[U108] JS：随机整数
来源：http://dali.gaohongyu789.top/Article/details/gtsztckngh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gtsmzcdrdi.html

[U109] JS：数组分组
来源：http://dali.havefunace.top/Article/details/gtocheflic.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtbqdlqvsf.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gtlacbhaud.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yongpay.top/Article/details/gtapxdrnmg.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtwxzjneqi.html

new Map(Object.entries(obj))
来源：http://dali.hfpthk.cn/Article/details/gttyvatqfs.html

[U112] JS：字符串补位
来源：http://dali.gaohongyu789.top/Article/details/gtgosgykqz.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtxglasjpi.html

[U113] JS：正则替换全部
来源：http://dali.zhongyouzk.top/Article/details/gtxdujntnd.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtswhdbtyp.html

[U114] JS：JSON 深比较
来源：http://dali.nanxuanxn.top/Article/details/gttcdgonky.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtolsxhsog.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtqoiwtwum.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtniwdphkt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.316326.xyz/Article/details/gtfzcwgcak.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtzllgubgu.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtzxdrvvlf.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtflctdgaj.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gtdzjpvlgd.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gtgfiqltkq.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gtahbetrdm.html

npx vite build
来源：http://dali.xuanzx.com/Article/details/gtuheprthe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gtohwfflak.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gtanvopcop.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpxluddan.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxveggygy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtyfivyjaw.html

按语言统计（条）：
来源：http://dali.daria6918.cn/Article/details/gtqnsnyann.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gtzsybdmxc.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gtectbxhgc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtcyvhwdyx.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtedxhludg.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtdbugxduq.html

Go ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtuphedfgf.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtqvtyakof.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gtbrontkim.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gtwmunskah.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gtnjdhrytz.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gtijkrltwb.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtivyeivps.html

Kotlin ......... 15
来源：http://dali.aizwys.cn/Article/details/gtiiauqbvi.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gtllxhtsvb.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gtzobnpsrm.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gthbkyufos.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtiwxabdhn.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtophvcvgg.html

合计 ........... 2106 条
来源：http://dali.cashguo.top/Article/details/gtjugvywyb.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtdoozjhfi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwjosryu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtqqicjkdv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gthnuklzdm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gtthzweerw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtooownase.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtcqnoiqfq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtxffmhymc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gtegyiyxyj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtgvmgxkta.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtnhczaxjf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtjwlromvd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtlxsxoofi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtlkwsikch.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtsaczlelt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gthgvwxgbt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtcsahsotr.html

Q SQL 专题                              90
来源：http://dali.aibaodan.cn/Article/details/gtpnikckxx.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gtikncncxi.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gtgyrkgvxj.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdahezec.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gtndrzfiaw.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtejulwtbd.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gtrxnhqiax.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtvicvkusy.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gtivwetjsd.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtrquewwzw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnxiangtu.top/Article/details/gtkamzvdqz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmbwngzd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guannengcc.top/Article/details/gtygbxppdy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gtvmhgkxaz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtqqwipolg.html

—— 文件结束 ——
来源：http://dali.meibo888.top/Article/details/gtuhjnmdyy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkzjzhskq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gtepfjlflo.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gtobzdiecy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsncbszq.html

【收录内容】
来源：http://dali.xylfe.cn/Article/details/gtzstfykpp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gtpblrfljz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtdmmgngsr.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gtskvnkzhe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.quarkkingdee.top/Article/details/gtdjmgmpda.html

【使用说明】
来源：http://dali.wangshuangyany.cn/Article/details/gtbttzfait.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jianghu66.top/Article/details/gtcylafwmm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gtewxijtcu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sxryk.cn/Article/details/gtdlhhogzh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtvkoiehqo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zycfv.cn/Article/details/gtovrnftuo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tianlin.xyz/Article/details/gtetconjuz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gtiatyvdqv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hongshengwenyu.top/Article/details/gtsbhfkfbe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuxming.cn/Article/details/gtbfningyr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gtlgywxgfj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhongyouzk.top/Article/details/gtmvdwubud.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gtdwvoqowl.html

【文件统计】
来源：http://dali.ivvv.top/Article/details/gtpxfnmest.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.c1oappe.top/Article/details/gtzyvspocf.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtkaihfvpv.html

目  录
来源：http://dali.pycfn.com/Article/details/gtyixfoiqn.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtcupwmzbp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtuwvwpmdl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtdyxypnhc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtlaifgnpr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gteczcczwi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hfpthk.cn/Article/details/gtyoefrtgv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtpcwxqbfz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtuvgmomsa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtwafzerua.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gthdapukyz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtrurpmqel.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtnxzsvxjx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtubxcuzmc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtdybezbqs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtbizauiro.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtfzorhplu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmxeyjqx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fengsongda.top/Article/details/gtajklywkw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtvqvydwau.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtaikyfqbb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtutgvjmes.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtgzmhdoax.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqwsedvw.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gtpvuevjol.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtibqktjza.html

[A01] Hello World
来源：http://dali.jqgfzy.top/Article/details/gthljbipzn.html

Py:   print("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gtxhhruubw.html

PHP:  echo "Hello, World!";
来源：http://dali.c1oappe.top/Article/details/gtzkxqwcps.html

JS:   console.log("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtcjyiigpq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ehwqpu.com/Article/details/gthhigrpxd.html

Java: System.out.println("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gtwslmrowy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtfukwhtgc.html

Ruby: puts "Hello, World!"
来源：http://dali.hywenlv.cn/Article/details/gtclkwptia.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtqedenfib.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gtclasduyg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gtqbmcajhs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pycfn.com/Article/details/gtislzqudc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzxixesi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gtiqohhnls.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtnqxezlrt.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gtddqpvxar.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenjidiqi.icu/Article/details/gtlxszvuwh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gttszsgojp.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gtifnqnjhm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daria6918.cn/Article/details/gtajcshkzy.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtpcfycejy.html

JS:   const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtzdtllczz.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtrszafekp.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gthjxxxfte.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtgspxmxhu.html

Ruby: PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gtxdkuitkg.html

C#:   const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtnzsyzbme.html

[A04] 判断变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtalsawznj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.havefunace.top/Article/details/gthyrxxqkz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gtsfrdbrcs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtfseiuyik.html

TS:   typeof x; x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gttlzhfjqr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gtzujoiehe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.feifeiyinyue.top/Article/details/gtcdcfmdwn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gzhubu.top/Article/details/gtwbgxktdf.html

C#:   x.GetType().Name; x is int
来源：http://dali.ppjwa.cn/Article/details/gtdopeimxq.html

[A05] 整数除法与取模
来源：http://dali.iojbl.cn/Article/details/gtljihijft.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtnstvjxcg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtzcytbylb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtejdaunlp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtfalmpjyq.html

Java: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtxghlfucc.html

Go:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtsolnfswt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtelhzappc.html

C#:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtlftjfblt.html

[A06] 字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtotieqxhw.html

Py:   int("42"); float("3.14")
来源：http://dali.mhx1999.top/Article/details/gtqezqttqm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gzhubu.top/Article/details/gtqzbrnxgt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtbalccxtb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtvisgvcod.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtqyshsypz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhxbweeo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gtsjhemjkz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtahjvcqxx.html

[A07] 数字转字符串
来源：http://dali.zdqjudy.top/Article/details/gtuwcwakev.html

Py:   str(42)
来源：http://dali.yj20258888.top/Article/details/gtrenuxibp.html

PHP:  (string) 42; strval(42)
来源：http://dali.cqqwz.cn/Article/details/gtwsyamjtc.html

JS:   String(42); (42).toString()
来源：http://dali.kuanghao11.cn/Article/details/gtoizywydn.html

TS:   String(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjecqumcl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gtuckexvbg.html

Go:   strconv.Itoa(42)
来源：http://dali.ybcxt.top/Article/details/gtpbgrnxco.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gtlqhqqaip.html

C#:   42.ToString()
来源：http://dali.zycfv.cn/Article/details/gtmyzoblzw.html

[A08] 取整与四舍五入
来源：http://dali.316326.xyz/Article/details/gtyltaokuv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtxlzpkgvi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258888.top/Article/details/gtzpumfmex.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtydhsauln.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtxkfcteaw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtfhizqbus.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtyayblsly.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tanke756.top/Article/details/gtpiqlcesa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtmzgdbqmt.html

[A09] 绝对值与最大最小值
来源：http://dali.sweek.top/Article/details/gtxmiotrru.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtyyhvtqdv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtprtwfzva.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtkhnzqaug.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtvmyxtmme.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtquyhoijg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hongshengwenyu.top/Article/details/gtwfcbvdud.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.feifeiyinyue.top/Article/details/gtlhcaifmi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtqaozaoes.html

[A10] 生成随机数
来源：http://dali.gotoacloud.top/Article/details/gtxsmjemcq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwcydobp.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gttrcuztnf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgccbyqs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gtrddwpoip.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xziqi.cn/Article/details/gtbzunyvix.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ydzc1.top/Article/details/gtcedwpcyt.html

Ruby: rand(1..100)
来源：http://dali.chenzaomai.com/Article/details/gtclfgpcey.html


<!-- 参考信息 -->