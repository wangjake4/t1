代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gtvxoymhmx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gtcutctsda.html

[U70] PHP：PDO 事务
来源：http://dali.xinyue.icu/Article/details/gtxoxkpiob.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtfqrknslp.html

[U71] PHP：抛出异常
来源：http://dali.zdqjudy.top/Article/details/gticsuuksh.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gttrueqeof.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gttkwqoyyr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zycfv.cn/Article/details/gtpmgfcjpe.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenlongwang.top/Article/details/gtwjiccapu.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtzzyysees.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtayryfxti.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cheryme.top/Article/details/gtqwthenva.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gttjjjudoh.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtkqarsjmw.html

[U76] PHP：简单路由
来源：http://dali.fengsongda.top/Article/details/gtcgfoulxy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zdqjudy.top/Article/details/gtzyzpvntd.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gtnsbovktj.html

composer require twig/twig
来源：http://dali.daria6918.cn/Article/details/gtkquejply.html

[U78] PHP：单元测试
来源：http://dali.hammf.cn/Article/details/gteterwitz.html

composer require --dev phpunit/phpunit
来源：http://dali.cqqwz.cn/Article/details/gtfwoonoji.html

[U79] PHP：静态分析
来源：http://dali.shuidangran.top/Article/details/gttuljxokm.html

composer require --dev phpstan/phpstan
来源：http://dali.snrcjt.cn/Article/details/gtnigvkbpx.html

[U80] PHP：代码规范修复
来源：http://dali.guowangkeji.top/Article/details/gtjvfzxrec.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtzmqzoswc.html

[U81] JS：初始化项目
来源：http://dali.dianchejie.cn/Article/details/gtdgqdhhkx.html

npm init -y;  npm i express
来源：http://dali.ivvv.top/Article/details/gttctkvwev.html

[U82] JS：package.json 脚本
来源：http://dali.birdmap.top/Article/details/gtnhreiwlz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigufen.top/Article/details/gtcqmrbbym.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gthuwnmhyo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtebyyrzlx.html

[U84] JS：CommonJS 写法
来源：http://dali.gzhubu.top/Article/details/gtpkaqogfq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fzhhl.top/Article/details/gtttytqusl.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gtdxkpffac.html

a?.b?.c
来源：http://dali.jinqigufen.top/Article/details/gtgwgjakem.html

[U86] JS：空值合并
来源：http://dali.yuanzhike.top/Article/details/gthnpykssn.html

a ?? b
来源：http://dali.chenzaomai.com/Article/details/gtlordomaw.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtoelolioh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ydzc1.top/Article/details/gtppnbkilm.html

[U88] JS：对象展开合并
来源：http://dali.guowangkeji.top/Article/details/gtltonyrfh.html

{ ...a, ...b }
来源：http://dali.zhengqikj.top/Article/details/gtdazbklie.html

[U89] JS：数组去重
来源：http://dali.zhengqikj.top/Article/details/gtvoqgyzkd.html

[...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtzgbaiuzz.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gtwlplsocq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtsvpntqer.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gttfwzqaka.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhixingplan.top/Article/details/gtxwugxvbr.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtwwwtliva.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtnlvqwujz.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgglgtgt.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gtpvjbwnki.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtsnhyycua.html

const double = x => x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtufpmlkak.html

[U95] JS：Promise 包装
来源：http://dali.gaohongyu789.top/Article/details/gtsvolbduw.html

new Promise((resolve, reject) => {})
来源：http://dali.xuanzx.com/Article/details/gttyjpexrf.html

[U96] JS：async/await 与异常
来源：http://dali.gotoacloud.top/Article/details/gtjzoiqpff.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtotjdgckg.html

[U97] JS：并发请求
来源：http://dali.ivvv.top/Article/details/gtbeiobmmu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtcajtmiqg.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gthuyncapf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.9152youxi.cn/Article/details/gtsvmfgwjk.html

[U99] JS：事件监听
来源：http://dali.iojbl.cn/Article/details/gtxhrwfkvf.html

el.addEventListener("click", e => {})
来源：http://dali.jqgufenzy.top/Article/details/gtgwhafpwz.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtihibcjdf.html

document.querySelector(".item")
来源：http://dali.zhiwuduotai.top/Article/details/gtzumgxkkv.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gtlppcplle.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gtprxwrbdk.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gtfxfqhjnp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gtsonlkwfb.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtxesejion.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtuufsqyao.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gtbgbkwloa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtlspjbcnm.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtobujxnua.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gtvicffsxl.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtpqtglyuk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtphflpzlb.html

[U107] JS：数字千分位
来源：http://dali.havefunace.top/Article/details/gtjvjwfiww.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj202588.top/Article/details/gtwqttvots.html

[U108] JS：随机整数
来源：http://dali.shangyingyoupin.top/Article/details/gtvwrcneux.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gtpfbeanzj.html

[U109] JS：数组分组
来源：http://dali.mhx1999.top/Article/details/gtuzpkfxxs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtdjpseqjk.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gtsnqutxnt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenlongwang.top/Article/details/gtajocudpe.html

[U111] JS：对象转 Map
来源：http://dali.meibo888.top/Article/details/gtqskrctkd.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gtbatpbeup.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gtroslvpcf.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtxwyauitd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gtvvoqrjxv.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtzmgoajsb.html

[U114] JS：JSON 深比较
来源：http://dali.cqqwz.cn/Article/details/gtnoskaqgk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtwduuyqvh.html

[U115] JS：生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtveuopkef.html

crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtnatnebwk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.snrcjt.cn/Article/details/gtfsnxixwc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gttxhhsvis.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gtiyfblyoz.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtuylsahdn.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtjxvcitpu.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtjesjmasg.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtsdoozkpn.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gtzmritaoq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hfpthk.cn/Article/details/gtyuraaads.html

import.meta.env.VITE_API_URL
来源：http://dali.quarkkingdee.top/Article/details/gtlfjaoedp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjyqdcogj.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtemwlwnid.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtljkpnwzf.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gtqfgmlmtg.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gtwyfsmhth.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gtmeucjhkn.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtilorymsm.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtkzpfywqf.html

Java ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtsgmdcxjl.html

Go ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwvlfveg.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gtawprhbth.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gtiqaayjpu.html

C .............. 30
来源：http://dali.kuanghao11.cn/Article/details/gtsyehcafr.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gtqqhypelm.html

SQL ............ 90
来源：http://dali.yj20258888.top/Article/details/gtjabwancj.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gtrsqarehp.html

Kotlin ......... 15
来源：http://dali.hysaishi.cn/Article/details/gtgqqojkrv.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtqgmndgkr.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtbzaqfush.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtmrnnfenh.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gtzcmdquwd.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtqzvcwpme.html

合计 ........... 2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtcgicoxmm.html

按章节统计：
来源：http://dali.vqdsnc.cn/Article/details/gtaexrmdrb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtuqjhsvzh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtqdukeqmn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtavthtecl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtgcppdmhx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.redwolf501.top/Article/details/gtajtrearf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gtaejqalmz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtujidrwfh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gteqavuphh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtekjxleki.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrwnfekz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtodfsprbk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtacaplioq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtnhylfvmb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgbvpwkv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.c1oappe.top/Article/details/gtvuuexvua.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gttbgzphrg.html

Q SQL 专题                              90
来源：http://dali.yonumen.top/Article/details/gtcvwbwiqb.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gtgunrccls.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtwtlfggij.html

T 其他语言补充                          60
来源：http://dali.svipenyu.cn/Article/details/gtglngigge.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gtwsfdlltg.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtznqteyfm.html

合计                                  2106 条
来源：http://dali.mhx1999.top/Article/details/gtcqdmwakj.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtkxseiyws.html

使用提醒
来源：http://dali.tanke756.top/Article/details/gtpskwnhhk.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtgafzieuf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gtfdexerdn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gtmjqsciiv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangdashe.top/Article/details/gtylpllbxq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtkqemhfil.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ybcxt.top/Article/details/gtlgplddhe.html

—— 文件结束 ——
来源：http://dali.zhiwuduotai.top/Article/details/gtjwgmbwun.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdududmky.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.vqdsnc.cn/Article/details/gtjkfrbiqy.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258.top/Article/details/gtiuldceoc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtznukuujl.html

【收录内容】
来源：http://dali.cucudq.cn/Article/details/gtlfbfiodp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hywenlv.cn/Article/details/gtzvbaamfd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yongpay.top/Article/details/gtpwtblrud.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtjnmnozcm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guowangkeji.top/Article/details/gtqtpnksnp.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtmjcgefzs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcmfyapr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gtldmlpybw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangdashe.top/Article/details/gtszcboyvc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tanke756.top/Article/details/gtpnofddjj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gtyetwnayl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sxryk.cn/Article/details/gtsumfocls.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hongshengwenyu.top/Article/details/gtjphrkrcc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gtnkzrkgto.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gtntxseios.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.haohaochexian.top/Article/details/gtrqczjwtd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtktcomyof.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtbsaxhgzd.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gtffyjkasg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ydzc1.top/Article/details/gtxmbonehx.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtkjufnejg.html

目  录
来源：http://dali.nanxuanxn.top/Article/details/gtafshqycb.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtmaxpbjym.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdayrysaw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtbvwjoyxw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtheitomum.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtpddcooux.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gtmkjwiqow.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sufxvd.cn/Article/details/gtusbvdvqp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtgriogmtx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.daxiang520.top/Article/details/gthehajkmy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtaxjvhstr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtgfpzdnsj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtkvmhohly.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtlkoeskiw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtqtdxeirb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gtbkadrslo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtjhwzavfv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtgtkebike.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jiagoushi.top/Article/details/gtgbltcvrf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gtilsjonrk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.birdmap.top/Article/details/gtpmekiohv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtvurkqmvn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtoyhnrofq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdxpmdzxz.html

A. 基础语法与类型
来源：http://dali.cheryme.top/Article/details/gtziornwrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthdwiwpmg.html

[A01] Hello World
来源：http://dali.jyoumei.cn/Article/details/gtzykpqoww.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtynorswra.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyypwjqps.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtzkcsntfh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gtaettjlgv.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtgkdujgdy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtucpbivax.html

Ruby: puts "Hello, World!"
来源：http://dali.cqqwz.cn/Article/details/gtrhujixqj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtpactfqtj.html

[A02] 变量声明与赋值
来源：http://dali.yj20258888.top/Article/details/gtszagavpp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shzxlz.cn/Article/details/gtbgziytdd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.bjfxy.top/Article/details/gtooscqeac.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gtvuqjpezj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jianghu66.top/Article/details/gtkghkmhqy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtdkknvjuh.html

Go:   name := "Alex"; age := 20
来源：http://dali.yueranfly.top/Article/details/gtzejtedco.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aizwys.cn/Article/details/gtnpycjibk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtwricwjxm.html

[A03] 常量定义
来源：http://dali.nwbrower.top/Article/details/gtvldioztd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tian-w.cn/Article/details/gtmwgrdmvn.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtdyofpehs.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtnofbonyq.html

TS:   const PI: number = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtpzkshrwe.html

Java: static final double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtvpezzqry.html

Go:   const PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtreffxxii.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gtnvuxttsz.html

C#:   const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtqeiktqdq.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gtjlrgqapt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guowangkeji.top/Article/details/gtireigtub.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwphmgbue.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gttzpnwjth.html

TS:   typeof x; x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtyqxpeysp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dianchejie.cn/Article/details/gtwemesnas.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.bjfxy.top/Article/details/gtafsumads.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gthtghhbrq.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenzaomai.com/Article/details/gtkwsyluuf.html

[A05] 整数除法与取模
来源：http://dali.dashuyun.cn/Article/details/gtdwdzmuov.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fzhhl.top/Article/details/gtpjuwasxz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtlyihabwn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gthmzlataf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtmrvbhfjm.html

Java: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gteyzgbdfh.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtigwrnxyl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtfveeezec.html

C#:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtbrzxniic.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtihkhwedt.html

Py:   int("42"); float("3.14")
来源：http://dali.ivvv.top/Article/details/gtoakwhfwz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaiisszj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtutbditgi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daria6918.cn/Article/details/gtzkohzioa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gtveywymvh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gtxsvxlghe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258.top/Article/details/gtpxrkfjaj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guannengcc.top/Article/details/gtkgmlomkw.html

[A07] 数字转字符串
来源：http://dali.tian-w.cn/Article/details/gtvldeiykw.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gtykgxhuwb.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gtsgygnztk.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtqmbkkzcj.html

TS:   String(42)
来源：http://dali.nwbrower.top/Article/details/gtgtfevkvl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daxiang520.top/Article/details/gtnijluwbs.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gthgaudgkj.html

Ruby: 42.to_s
来源：http://dali.jinqigufen.top/Article/details/gtrmpmanft.html

C#:   42.ToString()
来源：http://dali.zhixingplan.top/Article/details/gthchjabmw.html

[A08] 取整与四舍五入
来源：http://dali.wangshuangyany.cn/Article/details/gttetdxspw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtzpnikequ.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhoulong.xyz/Article/details/gtzyslmsfv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtmenymfzn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shzxlz.cn/Article/details/gtmsnigcfh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtmhjnoctg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtugldldgl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhpdheao.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtizsgnugr.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gtdnnwomuc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtaqijravu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtnhmauiix.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtuouucpak.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtcumdmnjb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtcsswqwtv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.redwolf501.top/Article/details/gtlmekdsfi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.daxiang520.top/Article/details/gtsrajlibu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ivvv.top/Article/details/gtdgxsvkpu.html

[A10] 生成随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtccwhyccp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.snrcjt.cn/Article/details/gtyeaxviyc.html

PHP:  random_int(1, 100);
来源：http://dali.cqqwz.cn/Article/details/gtfafhwsea.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtxxwcqdpj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtwxcifmgj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ivvv.top/Article/details/gtwaiqhzft.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fzhhl.top/Article/details/gtgxcscnen.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gtfquhluuz.html


<!-- 参考信息 -->