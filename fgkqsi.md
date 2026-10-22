代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gt2xkoppfvf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gt2pdptjagp.html

[U70] PHP：PDO 事务
来源：http://dali.xinyue.icu/Article/details/gt2cdjuxdpi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daria6918.cn/Article/details/gt2mjubskpw.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2ztxmddtf.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmmffbsl.html

[U72] PHP：写错误日志
来源：http://dali.ivvv.top/Article/details/gt2vuzccnap.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shzxlz.cn/Article/details/gt2ndlmidod.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gt2vrmlekvf.html

parse_ini_file("config.ini", true)
来源：http://dali.yuanzhike.top/Article/details/gt2akwhdfqv.html

[U74] PHP：读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbvgpvhk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptbskcib.html

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gt2pvyxqott.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gt2bzjjthtf.html

[U76] PHP：简单路由
来源：http://dali.jyoumei.cn/Article/details/gt2fhtwarrb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gt2zjuzmlux.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjklzjmk.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gt2jnlukdjl.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gt2yihzddpb.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gt2ouadvdna.html

[U79] PHP：静态分析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wquwrkvw.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gt2rjmfognq.html

[U80] PHP：代码规范修复
来源：http://dali.svipenyu.cn/Article/details/gt2umnpnnor.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xinyue.icu/Article/details/gt2exiptyfe.html

[U81] JS：初始化项目
来源：http://dali.chenzaomai.com/Article/details/gt2jasybgyr.html

npm init -y;  npm i express
来源：http://dali.jyoumei.cn/Article/details/gt2xyoprykk.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gt2dtaeqknw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrvofvev.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gt2lplsksly.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gt2fqpoptpa.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gt2mwktmxxb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gt2chtqzonx.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gt2zggiwadc.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gt2dgajbnjb.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gt2rgedjdap.html

a ?? b
来源：http://dali.zhengqikj.top/Article/details/gt2qrpznias.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvpcogrl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnarqgvg.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gt2zogcnzfb.html

{ ...a, ...b }
来源：http://dali.meibo888.top/Article/details/gt2fwvidqpf.html

[U89] JS：数组去重
来源：http://dali.yueranfly.top/Article/details/gt2rllnnypy.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2mraferrh.html

[U90] JS：数字数组排序
来源：http://dali.dashuyun.cn/Article/details/gt2dkfbgbca.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2djbhlrur.html

[U91] JS：对象键值遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2efqolnrj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmhdpzgv.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gt2fnwawyye.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2emjdwrpu.html

[U93] JS：模板字符串
来源：http://dali.zhengqikj.top/Article/details/gt2bsxwgdzn.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gt2ofrcfxyu.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gt2scqaltsd.html

const double = x => x * 2;
来源：http://dali.sxryk.cn/Article/details/gt2mlxndjng.html

[U95] JS：Promise 包装
来源：http://dali.zhixingplan.top/Article/details/gt2ydriqyex.html

new Promise((resolve, reject) => {})
来源：http://dali.yanxiufei.cn/Article/details/gt2gjpcfwko.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gt2zmiczgcx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2fyjazjya.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gt2cjgubsmp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2pfsoviko.html

[U98] JS：fetch 带 JSON
来源：http://dali.xylfe.cn/Article/details/gt2khlkdxlf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gt2vowxhflc.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gt2balqhuue.html

el.addEventListener("click", e => {})
来源：http://dali.316326.xyz/Article/details/gt2lymlskrs.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gt2ugwsdnyy.html

document.querySelector(".item")
来源：http://dali.ppjwa.cn/Article/details/gt2qjakzqvf.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gt2kukyrwfw.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2yymcxkhf.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gt2jpmoyogl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cashguo.top/Article/details/gt2clpylyce.html

[U103] JS：定时器
来源：http://dali.ivvv.top/Article/details/gt2nquzvzxo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhiwuduotai.top/Article/details/gt2niujwvdc.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrjhjtzl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2tpobbqvp.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gt2iczuckyp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yufzydxt.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gt2bpvmntel.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dianchejie.cn/Article/details/gt2ystvpvtz.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pczysvsq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2avbfzhdj.html

[U108] JS：随机整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lniygiua.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gt2krvxzjcf.html

[U109] JS：数组分组
来源：http://dali.xylfe.cn/Article/details/gt2izhytiek.html

Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2ajzvyyer.html

[U110] JS：数组分块
来源：http://dali.gogol.net.cn/Article/details/gt2qtiguddx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ycputgto.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gt2bwegdars.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gt2qngmlmuh.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gt2iqafajaj.html

"7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klptkkyu.html

[U113] JS：正则替换全部
来源：http://dali.guannengcc.top/Article/details/gt2kymowqfw.html

s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2gduvxobw.html

[U114] JS：JSON 深比较
来源：http://dali.yonumen.top/Article/details/gt2gastvxil.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2opvsbkqv.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2xllidgny.html

crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2lqxuvwej.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gt2ckkkqhiv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yongpay.top/Article/details/gt2pwfomhue.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2fyitxxlw.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gt2vfkcglgy.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gt2bgcdttac.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gt2molzmfxq.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gt2wujkurpy.html

npx vite build
来源：http://dali.birdmap.top/Article/details/gt2rwuvezto.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2depdvzdg.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gt2hskgryya.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2yzjzjtyt.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gt2cxydsqqh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vzlyadol.html

按语言统计（条）：
来源：http://dali.jiagoushi.top/Article/details/gt2fdeybwuu.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izlgjdai.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gt2zyafkiwz.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gt2mowsswlg.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gt2ruuvhpho.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gt2orthptzh.html

Go ............. 212
来源：http://dali.jinqigufen.top/Article/details/gt2okdiwdbh.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gt2mlsxqmhv.html

C# ............. 212
来源：http://dali.jyoumei.cn/Article/details/gt2zgtbhpal.html

C .............. 30
来源：http://dali.ybcxt.top/Article/details/gt2pstotfpg.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gt2tfydtmlp.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gt2jpxgdivz.html

Bash ........... 80
来源：http://dali.dashuyun.cn/Article/details/gt2sunpkdym.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gt2xgyytcqx.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gt2bwegcnme.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gt2igdkuzot.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2wcerreqd.html

Scala .......... 10
来源：http://dali.jinqigufen.top/Article/details/gt2fitdrlgd.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2yvuphqqg.html

合计 ........... 2106 条
来源：http://dali.andypj.xyz/Article/details/gt2gjupiwbz.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gt2xeoeyxkn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjafyoyg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2aujuwubc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2katfpwch.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gt2xhrayrzp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yvedp.cn/Article/details/gt2ikkndlhx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gt2fxzwjkrc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2qlfeupjn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gt2tduebaok.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2jghxfyea.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2ykchmofk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2qspgliux.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2mdvasbia.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2gsiwwjoq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gt2hfaqftui.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gt2fpvghree.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2fhnrfpte.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gt2kyaamyem.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gt2arlhlokd.html

S C / C++ 专题                          60
来源：http://dali.hongshengwenyu.top/Article/details/gt2znupyxkd.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gt2ecwotewk.html

U 高频实用片段                         120
来源：http://dali.aibaodan.cn/Article/details/gt2kpbzgftd.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2zjyqacoj.html

合计                                  2106 条
来源：http://dali.xuanzx.com/Article/details/gt2ududwqyy.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2tubropkq.html

使用提醒
来源：http://dali.zhongyouzk.top/Article/details/gt2nbciqhyx.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2ldcvpscc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hammf.cn/Article/details/gt2dphfzfyd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gt2slzmwjfv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aibaodan.cn/Article/details/gt2lnxafifi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gt2bgmxeyzd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sweek.top/Article/details/gt2wziexpsd.html

—— 文件结束 ——
来源：http://dali.aibaodan.cn/Article/details/gt2binlwmci.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tscapwla.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnxiangtu.top/Article/details/gt2ijgexcbn.html

Common Programming Examples Cheat Book
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzfibihz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2fifihtdz.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gt2fldirvwj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.c1oappe.top/Article/details/gt2udctlqfp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ehwqpu.com/Article/details/gt2ipzyzill.html

SQL · Bash · C · C++
来源：http://dali.redwolf501.top/Article/details/gt2ypllllpg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.andypj.xyz/Article/details/gt2dgwkoxoz.html

【使用说明】
来源：http://dali.andypj.xyz/Article/details/gt2lwuhriqy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gt2qosnzajb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.0kj1m.cn/Article/details/gt2pqkbmttw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj202588.top/Article/details/gt2xdmybyxv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gt2pmybuquy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.andypj.xyz/Article/details/gt2qhzlfxga.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.0kj1m.cn/Article/details/gt2aexyniem.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gt2armfdpos.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gt2aofeeatc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gt2ibhosaqr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sufxvd.cn/Article/details/gt2qfrnildk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.bjfxy.top/Article/details/gt2lgogxdiy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gt2ljsprnzw.html

【文件统计】
来源：http://dali.nanxuanxn.top/Article/details/gt2lcqlocef.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gt2egilfefz.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gt2lrhbsuoh.html

目  录
来源：http://dali.xuanzx.com/Article/details/gt2dnfjitxz.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2gcpblugd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2foeyosjo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2zymatolq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gt2cqvxefkd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gt2rnnosoht.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zdqjudy.top/Article/details/gt2lnhlltkc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gt2ccjfzmyf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gt2zigzfbxg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2uehcwfoj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2ssujiumv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gt2ybpkaksl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gt2rltravkg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2joeidxrs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2afqqaxdr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gt2sqmpozwl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gogol.net.cn/Article/details/gt2xtmfkgqg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvynyvsl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guowangkeji.top/Article/details/gt2kpixqpbt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gt2ogswqbuj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fzhhl.top/Article/details/gt2oraoruno.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2llgryhhe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2tifttzkc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2meluqioj.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmumumyy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pgasyryz.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2jnhfadei.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmggsasc.html

PHP:  echo "Hello, World!";
来源：http://dali.hywenlv.cn/Article/details/gt2tpmntkys.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvpsevif.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gt2mirvswyi.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2jihrdgym.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gt2ecmpkbht.html

Ruby: puts "Hello, World!"
来源：http://dali.316326.xyz/Article/details/gt2ixiurqtk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gt2rncamdsq.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssnnjveo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejdzhcch.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2phmjfzkn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2ycoxolxm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2kosekqdc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2uxutmpvk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zdqjudy.top/Article/details/gt2xjvlhjnx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2joqjlklu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2zdrjcgwe.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gt2mybrhbeh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqezdsjp.html

PHP:  const PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2swvkldkz.html

JS:   const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2nvrkiqvq.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrsndrqd.html

Java: static final double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2sxaiekry.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gt2uyampbei.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gt2rjjyvqgw.html

C#:   const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2akcjphtr.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2xnmqlfri.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.smart0.xyz/Article/details/gt2psdflqsn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aibaodan.cn/Article/details/gt2tcnjoaxk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2rztyjaow.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gt2faypnwao.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sopohpuc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gt2adppfkxd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzuxxhlc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gt2dtsersbb.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gt2gtrmozsj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jyoumei.cn/Article/details/gt2clcrrbcg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2ruftducu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2bgvgjpsi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2jvartzuv.html

Java: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2bkefnpvf.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2slcrhajn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2vhzzsyln.html

C#:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2mqslayfj.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2opgdiqpc.html

Py:   int("42"); float("3.14")
来源：http://dali.tanke756.top/Article/details/gt2rgofzzyj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guannengcc.top/Article/details/gt2hngbaqxv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tanke756.top/Article/details/gt2nhrldbeh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gt2lzsktcpa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aizwys.cn/Article/details/gt2idewjgyu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqcolpvv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gt2rxufnsrx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gzhubu.top/Article/details/gt2sobvpdcq.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gt2hqydgsxf.html

Py:   str(42)
来源：http://dali.gzhubu.top/Article/details/gt2gtezeomf.html

PHP:  (string) 42; strval(42)
来源：http://dali.birdmap.top/Article/details/gt2poedtkuw.html

JS:   String(42); (42).toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlprgkcg.html

TS:   String(42)
来源：http://dali.yvedp.cn/Article/details/gt2kjzwnzry.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuxming.cn/Article/details/gt2zsbdiusy.html

Go:   strconv.Itoa(42)
来源：http://dali.hywenlv.cn/Article/details/gt2opvrjnno.html

Ruby: 42.to_s
来源：http://dali.kuanghao11.cn/Article/details/gt2lxfvfzzq.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gt2yrrdghjz.html

[A08] 取整与四舍五入
来源：http://dali.bjfxy.top/Article/details/gt2ldesoncp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kupcxfad.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.0kj1m.cn/Article/details/gt2jkcdnwdx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2kuvmfhrf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gt2fixgafuw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lauxkeva.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2rtyrmqeo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmtxkprr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2tiqrgvxe.html

[A09] 绝对值与最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2cmcevyec.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2evholfml.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2vbiqhadq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2ttcegaql.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2byycmbyc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2kvcsmkly.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gt2tntrheey.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cheryme.top/Article/details/gt2wsewvvqf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2qbjvuvfc.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gt2yjzggjce.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sweek.top/Article/details/gt2zvcyvddr.html

PHP:  random_int(1, 100);
来源：http://dali.wangdashe.top/Article/details/gt2fnqlwezi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yvedp.cn/Article/details/gt2ncdbmgcc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gt2cflwjzii.html

Java: new Random().nextInt(100) + 1
来源：http://dali.havefunace.top/Article/details/gt2yxspekpk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daxiang520.top/Article/details/gt2kqobsviu.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtkejtrb.html


<!-- 参考信息 -->