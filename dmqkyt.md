代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtbmjdavjk.html

throw new RuntimeException("失败", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtxgmjzyrd.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtuyxuifkm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gtppmxqeck.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuanzx.com/Article/details/gtldrghwzb.html

parse_ini_file("config.ini", true)
来源：http://dali.guowangkeji.top/Article/details/gtgcnpjjra.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtybishkqw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ppjwa.cn/Article/details/gtwuwltbid.html

[U75] PHP：依赖注入
来源：http://dali.cqqwz.cn/Article/details/gtbfqbaqrv.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gtwpjahhbc.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gtjlkwxnvp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gtfnonbqmw.html

[U77] PHP：模板渲染
来源：http://dali.ppjwa.cn/Article/details/gtzkhhawuc.html

composer require twig/twig
来源：http://dali.wangshuangyany.cn/Article/details/gtgtolvvyw.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gtcphmlwys.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwqnyhww.html

[U79] PHP：静态分析
来源：http://dali.hnxiangtu.top/Article/details/gtyjatfxql.html

composer require --dev phpstan/phpstan
来源：http://dali.cqqwz.cn/Article/details/gtxidggncy.html

[U80] PHP：代码规范修复
来源：http://dali.tian-w.cn/Article/details/gtqxvsmrij.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.iojbl.cn/Article/details/gtnskjclmy.html

[U81] JS：初始化项目
来源：http://dali.tianlin.xyz/Article/details/gtahpzmrfo.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtakffxvbd.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gtqcstxawm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gtkvyvafvl.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtrdnjseij.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtqeslmqma.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgfzy.top/Article/details/gtnhtpayik.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yongpay.top/Article/details/gtofrmbrur.html

[U85] JS：可选链
来源：http://dali.xuanzx.com/Article/details/gtooftnvpd.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gtwlrgwkqe.html

[U86] JS：空值合并
来源：http://dali.ivvv.top/Article/details/gtqkkieych.html

a ?? b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuhhicjc.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtulhtjnha.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gtsrybjbit.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtcehlzvln.html

{ ...a, ...b }
来源：http://dali.yuanzhike.top/Article/details/gtxmbfwhbk.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gtzphfzygz.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtbrjkmmuq.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcifdfukh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gttcfrxkur.html

[U91] JS：对象键值遍历
来源：http://dali.cashguo.top/Article/details/gtjukvhqqj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jyoumei.cn/Article/details/gtadfcocvl.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtsozrolcf.html

structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtqgepthtz.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gtinxuvdss.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gtaxwceafp.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtdkqhhqtg.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gtzqkzilch.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtyglyppvx.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gtlsdudfsn.html

[U96] JS：async/await 与异常
来源：http://dali.hammf.cn/Article/details/gtcwjakiqh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtbtwklcom.html

[U97] JS：并发请求
来源：http://dali.c1oappe.top/Article/details/gtuqxymxsg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtgvqrhjab.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gtkjliyhiu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuxming.cn/Article/details/gtmwjphmvp.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gtwquqbmek.html

el.addEventListener("click", e => {})
来源：http://dali.iojbl.cn/Article/details/gtukuzmgtv.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gttvyjopqi.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gtvwimbtgc.html

[U101] JS：classList 操作
来源：http://dali.tian-w.cn/Article/details/gtieusqntw.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkibfenk.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gtioyquuzv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gtorftvfpu.html

[U103] JS：定时器
来源：http://dali.hnxiangtu.top/Article/details/gtaiwzhoih.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gthrsgwnbx.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gtxczoeuzu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtzvykvaqy.html

[U105] JS：节流
来源：http://dali.zhengqikj.top/Article/details/gtdnwjcthb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gtkmjykqnq.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtjhnokidu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gtdszafmxo.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtdxibrcfe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtyxxdtpum.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtnlozvkhz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gtzdyhvwqx.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gtlemkdoml.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtqipqzacw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gtgyvbsdvy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.vqdsnc.cn/Article/details/gtnivllrwp.html

[U111] JS：对象转 Map
来源：http://dali.chenzaomai.com/Article/details/gthzjdbbga.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gtnubfciyp.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gtsvddcsmz.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtscsdurzc.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gttjkuuurt.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtbecoheaj.html

[U114] JS：JSON 深比较
来源：http://dali.smart0.xyz/Article/details/gtvznzcsnk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gthidvzsrg.html

[U115] JS：生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtjrlssrft.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtjubfaccl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gtbqzsqkqw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtjxzdodin.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtbouedykl.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gttblpcdta.html

[U118] JS：开发服务器
来源：http://dali.dianchejie.cn/Article/details/gtrxxebxbr.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gtnpaufptr.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gtyjzoedlc.html

npx vite build
来源：http://dali.c1oappe.top/Article/details/gtsourxnwh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gtlqretnyt.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtlmkitifa.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjwvdtlcq.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gtohrptmzf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtauwdvpfp.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gtiebodjks.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gthljmbpef.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gtdivnrnzx.html

JavaScript ..... 252
来源：http://dali.zhixingplan.top/Article/details/gtnhcwimqc.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtsbkxjfys.html

Java ........... 212
来源：http://dali.birdmap.top/Article/details/gtmynhjutl.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gtrzwbjizu.html

Ruby ........... 212
来源：http://dali.c1oappe.top/Article/details/gtmlqemfno.html

C# ............. 212
来源：http://dali.ydzc1.top/Article/details/gtvzmtwhce.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gtuxjapmfl.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gtewbcnkhu.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gtbtqvgsvt.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gthwdgptzm.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtniivtmpu.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtsacfrrwh.html

Lua ............ 10
来源：http://dali.316326.xyz/Article/details/gtbqxypplu.html

Perl ........... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtssoiaxuz.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gtlooinprd.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtcjxdeqpl.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gttfonjudh.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtidkkmdcw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtrufokgyy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtvpzzwshb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtjlgiyuic.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ybcxt.top/Article/details/gtzobsfqfk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gtfaloboaw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nanxinkj.top/Article/details/gthkfaopwk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gteuemjhyk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gtcucongfg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtfvhtmxue.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtubaqikkm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtomijxesc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtdripuryn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtjuwszpkc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtbgiwjzdq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gtehozgras.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtlsjupama.html

Q SQL 专题                              90
来源：http://dali.tian-w.cn/Article/details/gtyckhwyim.html

R Bash 专题                             80
来源：http://dali.hysaishi.cn/Article/details/gtjtsgpovi.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gttihwwmmj.html

T 其他语言补充                          60
来源：http://dali.jyoumei.cn/Article/details/gtdubqfxsl.html

U 高频实用片段                         120
来源：http://dali.yueranfly.top/Article/details/gtwnihfiwo.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtwlundwml.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gthmjpwrwg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtlgggskzu.html

使用提醒
来源：http://dali.ivvv.top/Article/details/gtoiyeitls.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtiedsjsfb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gtzmnmlntk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gzhubu.top/Article/details/gtpgtdotqf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cashguo.top/Article/details/gtpjxaqmjl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dianchejie.cn/Article/details/gtlqenztjz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigfzy.top/Article/details/gthwrbvnpl.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gtoxjrtviu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcynthegb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gtozosvyxw.html

Common Programming Examples Cheat Book
来源：http://dali.hysaishi.cn/Article/details/gtgcppldnu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofydcnlw.html

【收录内容】
来源：http://dali.cqqwz.cn/Article/details/gtsiejdzxv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezgajpst.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hnxiangtu.top/Article/details/gtpimiryzy.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gtxeloqosu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmdljbzq.html

【使用说明】
来源：http://dali.yanxiufei.cn/Article/details/gtvrqnfpav.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cdnleiting.top/Article/details/gttrrzhrhi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gtmzzngpnm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgfzy.top/Article/details/gttkhhdpcg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.feifeiyinyue.top/Article/details/gtetzzulaa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gtqhuftbmn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gttrikqiqq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gtrkdbttsn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gtsimsmost.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gtjtqshlbj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dashuyun.cn/Article/details/gtrykekohf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gtsohkeelz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ydzc1.top/Article/details/gtzloimcvn.html

【文件统计】
来源：http://dali.yuanzhike.top/Article/details/gtgzoxdycz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yangfankeji.com/Article/details/gtzgvnxabo.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtshoiqwqc.html

目  录
来源：http://dali.yuanzhike.top/Article/details/gthmsutzvf.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gteirvvmgw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtokltrhqp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtjvqvhiib.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtevpsrvjl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gtazzkgspp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.0kj1m.cn/Article/details/gtuxqbrary.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gtsamfrvxq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtffylstsa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gttgxfkopy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtwfhcpsch.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtbwddtsnr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtgvxgfpvh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtaojkhucx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gteskfxgso.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtihbjsrnk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxinkj.top/Article/details/gtueucjgkh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtvkmizouf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtldlwyddi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtlbczzppb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cheryme.top/Article/details/gtzpjvsfix.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtclwvmnbf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtucqtjwjd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtctnabapa.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gtoyqeqxrh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxhxinhal.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtspfqmzgm.html

Py:   print("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtfxvaoifw.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gtddfgkezz.html

JS:   console.log("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gthqfpwjzh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shzxlz.cn/Article/details/gtujetxeex.html

Java: System.out.println("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gthetbfbdr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yongpay.top/Article/details/gtnhhyoxgr.html

Ruby: puts "Hello, World!"
来源：http://dali.hammf.cn/Article/details/gtgtobwgfh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtukievazu.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gtiwibmkaj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtrvmepprt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtysxdlrvx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.bjfxy.top/Article/details/gtkssunqvw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hfpthk.cn/Article/details/gtznhszbtg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtkvqxqafh.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj202588.top/Article/details/gtqnoyhjpm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gtuktcuhfk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sxryk.cn/Article/details/gtxozfwmgj.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gtxtpyupew.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gogol.net.cn/Article/details/gtueaqxvlq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtfbujzggj.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtlhcafgum.html

TS:   const PI: number = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gthvpxblbe.html

Java: static final double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtiftezkbg.html

Go:   const PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtcitdyvfa.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzcpytkn.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtwnteqtnf.html

[A04] 判断变量类型
来源：http://dali.xziqi.cn/Article/details/gtkaogwpvh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gogol.net.cn/Article/details/gtyfeztqtq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.redwolf501.top/Article/details/gtwkhnhnxp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtwxrobnpq.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gtzuiceebj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gtudzrfjml.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.mhx1999.top/Article/details/gtxcjxxgxc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtlnclyrkv.html

C#:   x.GetType().Name; x is int
来源：http://dali.hywenlv.cn/Article/details/gtbbfhjsey.html

[A05] 整数除法与取模
来源：http://dali.havefunace.top/Article/details/gtzmgclbbt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shangyingyoupin.top/Article/details/gtgkphwdux.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyxcpank.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtahwnrjaf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtxaiwwfcw.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtvgmqrlyr.html

Go:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtykdbhfim.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtghgocehm.html

C#:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtonssnqfy.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtqvfemtrv.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtepdjivyc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guannengcc.top/Article/details/gtmbdgivyr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daria6918.cn/Article/details/gtlvicukiw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozgglrcz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtcyjvdbeb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gtvqjoxyjc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.feifeiyinyue.top/Article/details/gtxjrdvcku.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtghdhedsj.html

[A07] 数字转字符串
来源：http://dali.0kj1m.cn/Article/details/gtfuubtwlq.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gtijnyzmuu.html

PHP:  (string) 42; strval(42)
来源：http://dali.guannengcc.top/Article/details/gtctajvqpb.html

JS:   String(42); (42).toString()
来源：http://dali.dianchejie.cn/Article/details/gtsnohboiq.html

TS:   String(42)
来源：http://dali.meibo888.top/Article/details/gtwlkhirzy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gtgkfclhxj.html

Go:   strconv.Itoa(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwflajidj.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gtpduozmhj.html

C#:   42.ToString()
来源：http://dali.snrcjt.cn/Article/details/gtqmhrtrip.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gtraupqacz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtkmkrfnqf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.havefunace.top/Article/details/gtugotqsgh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtpmpxutbn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.haohaochexian.top/Article/details/gtbsnljgzo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtdrnweflf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtotytnyba.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gtgzxwulxu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtdovpzukv.html

[A09] 绝对值与最大最小值
来源：http://dali.xziqi.cn/Article/details/gtvksevyit.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtgyscvaab.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtjoqjfajc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleayzynp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtddsivspw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtagwzwfjw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gotoacloud.top/Article/details/gtzzgmkbwe.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gtgaghkhpf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtkwmektaa.html

[A10] 生成随机数
来源：http://dali.quarkkingdee.top/Article/details/gtpityglky.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuetiantiany.cn/Article/details/gtnbaigvrq.html

PHP:  random_int(1, 100);
来源：http://dali.redwolf501.top/Article/details/gtxvanpojp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gaohongyu789.top/Article/details/gtfgqrcova.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gthepdrkgh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fzhhl.top/Article/details/gtwvwvyvjl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjjdpuug.html

Ruby: rand(1..100)
来源：http://dali.sufxvd.cn/Article/details/gtkcgzvapb.html

C#:   new Random().Next(1, 101)
来源：http://dali.cashguo.top/Article/details/gttnjcexaf.html

[A11] 条件表达式（三元）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmteedhb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gotoacloud.top/Article/details/gtvrettytd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtzrcajrdz.html


<!-- 参考信息 -->