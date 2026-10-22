代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gt2umejxuev.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gt2qpuzsaue.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gt2lzuevxbd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.andypj.xyz/Article/details/gt2wuwgypmb.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsfwzkbp.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gt2fqlhuhez.html

[U72] PHP：写错误日志
来源：http://dali.chenzaomai.com/Article/details/gt2sbplfdpp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upefdjoa.html

[U73] PHP：读取 ini 配置
来源：http://dali.yangfankeji.com/Article/details/gt2ssywjlxb.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gt2uczyxxje.html

[U74] PHP：读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2kqemisuz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gt2lolnfafc.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gt2qsgrtmbe.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpwltrqk.html

[U76] PHP：简单路由
来源：http://dali.ehwqpu.com/Article/details/gt2gnzelzpg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjgrbcjq.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gt2lwlmpjey.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gt2yewygkdd.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gt2fcnyyzwt.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gt2wbmnerus.html

[U79] PHP：静态分析
来源：http://dali.quarkkingdee.top/Article/details/gt2xixagoyj.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gt2ivxmwnpd.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gt2zvpenasc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gt2kqqtnsgb.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gt2ltjkaocq.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gt2grijbvbd.html

[U82] JS：package.json 脚本
来源：http://dali.ybcxt.top/Article/details/gt2dinczocw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gt2odiayyeh.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gt2rndkjreb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gt2vvvvghbj.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjjemqnn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gt2ylcrdulq.html

[U85] JS：可选链
来源：http://dali.cheryme.top/Article/details/gt2usfvpkgh.html

a?.b?.c
来源：http://dali.sweek.top/Article/details/gt2lumneiru.html

[U86] JS：空值合并
来源：http://dali.zhixingplan.top/Article/details/gt2xtdsfcwi.html

a ?? b
来源：http://dali.cdnleiting.top/Article/details/gt2qhfqlvns.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gt2oqhlhwvx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gt2qcyyrgad.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gt2rkumljrj.html

{ ...a, ...b }
来源：http://dali.fzhhl.top/Article/details/gt2foqflumk.html

[U89] JS：数组去重
来源：http://dali.jlsjyb.cn/Article/details/gt2kksofuss.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2nmowhqrk.html

[U90] JS：数字数组排序
来源：http://dali.zdqjudy.top/Article/details/gt2xbcvrrjl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2iwexdigj.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gt2cbvhlusk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gt2sgpxvyvk.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvqxliwg.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2trukzpdt.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gt2bffrbnmt.html

`共 ${n} 条`
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttouynpr.html

[U94] JS：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gt2plgrcwjr.html

const double = x => x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gt2nunasvms.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gt2oeneowig.html

new Promise((resolve, reject) => {})
来源：http://dali.ybcxt.top/Article/details/gt2vlgcvfnk.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezompqhv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2ohywpmxq.html

[U97] JS：并发请求
来源：http://dali.pycfn.com/Article/details/gt2bldlvben.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2vowkoqse.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2bpseoqhk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ppjwa.cn/Article/details/gt2xtmvoevz.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gt2oxnxociv.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gt2bsvvmvza.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gt2ohtecfcn.html

document.querySelector(".item")
来源：http://dali.sufxvd.cn/Article/details/gt2sjdcdjhs.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gt2pgfnoazf.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2naatwpxx.html

[U102] JS：本地存储
来源：http://dali.guannengcc.top/Article/details/gt2ejiilrgl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxuanxn.top/Article/details/gt2bvnykbah.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igmivnan.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hfpthk.cn/Article/details/gt2gmjjamfn.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gt2emnvfecs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2becikzhg.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gt2fnufkyns.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zycfv.cn/Article/details/gt2bmxftpbp.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2djjupzoq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tian-w.cn/Article/details/gt2svazumzp.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2naaatdcx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2sdwkmnqx.html

[U108] JS：随机整数
来源：http://dali.tian-w.cn/Article/details/gt2beaabdkm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hfpthk.cn/Article/details/gt2zcoudjwr.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gt2akgiekbb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2mtssjvjj.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gt2iccpfgsn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hysaishi.cn/Article/details/gt2nulrohwt.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udihkkqo.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aopursnx.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gt2yhkqxeok.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2xozsfhsn.html

[U113] JS：正则替换全部
来源：http://dali.havefunace.top/Article/details/gt2ezhtgzqc.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2jkrbsyxc.html

[U114] JS：JSON 深比较
来源：http://dali.jyoumei.cn/Article/details/gt2iseyptux.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gt2dyswfdpt.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gt2wtvvjqqa.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2nhwsdrfm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gt2kmvzagvn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gt2bdzzmbja.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2qenfybby.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gt2myveesrk.html

[U118] JS：开发服务器
来源：http://dali.vqdsnc.cn/Article/details/gt2awscndyw.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gt2peduvdyl.html

[U119] JS：生产构建
来源：http://dali.zycfv.cn/Article/details/gt2aolguipa.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gt2bkfbygzf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gt2fysctzdy.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gt2tmnegkxm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bbglfott.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gt2nwrkzdos.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ntfierxs.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gt2sbllelgb.html

Python ......... 252
来源：http://dali.zhixingplan.top/Article/details/gt2nrxxreid.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gt2mjiajcuq.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gt2vsqkmbey.html

TypeScript ..... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzqpxkio.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2fabzhzbp.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gt2ekmleail.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqxhingo.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gt2bbtotbxn.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gt2akcbemvj.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gt2dothtvdz.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gt2ucarxvfd.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gt2iupogoog.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gt2xwsseezv.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2pguiclmz.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gt2ydlsctkk.html

Perl ........... 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2unaoxjmp.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gt2egspnvaz.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2duzuvdmt.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2cwkhldtz.html

按章节统计：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqqjsoww.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gt2jvdiowdi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2xciikfzs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjcrqgjd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2qyrrjcwa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwshnvem.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gt2jrcphbsb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gt2shhurshg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2evugghah.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2dvhavozj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gt2bsablkti.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2mlzyzwwo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2kctewrtk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2hnlxaycw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gt2fwzyunry.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gt2gmjlkhhc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2njabqqjc.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gt2ohmjvhzu.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gt2nvfaukme.html

S C / C++ 专题                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iupidbkp.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gt2hfibmpdx.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoiqfehm.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2lkszrxsx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqgznms.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2xcvnqgeb.html

使用提醒
来源：http://dali.zhengqikj.top/Article/details/gt2iatvyzvg.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2fdonjmht.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gt2ypjuyqox.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gt2deocarcb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boazyooy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fzhhl.top/Article/details/gt2xcqrfifu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gt2utfcgear.html

—— 文件结束 ——
来源：http://dali.hnqzz.top/Article/details/gt2jonqiqfr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kupbzogz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gt2ikgnamqr.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gt2typlycck.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2vluegede.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzoipnnh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gt2ghzawijl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.smart0.xyz/Article/details/gt2cjdflzbi.html

SQL · Bash · C · C++
来源：http://dali.vqdsnc.cn/Article/details/gt2bituzwaa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ydzc1.top/Article/details/gt2rcngqrjy.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyzorfwx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgqilivo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylszskeq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.kuanghao11.cn/Article/details/gt2sprbciou.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsuctpye.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gt2lneiectn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mksozetf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gt2amsdcqqr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gt2xyonznwi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2caydnlof.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gt2tqbwhjau.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gt2ynldpmuy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuanzx.com/Article/details/gt2hcuaxwbj.html

【文件统计】
来源：http://dali.hnqzz.top/Article/details/gt2fmunflwk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgufenzy.top/Article/details/gt2eymhgput.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2szgmubqy.html

目  录
来源：http://dali.316326.xyz/Article/details/gt2ufzvqcaq.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2shjspmvh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gt2hsoaintb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gt2kkdthjfj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2xfgmblbk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2cytbjrhd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yongpay.top/Article/details/gt2xfawgclw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gt2pfcmtefn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gt2ppezbhvx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gt2tysheitc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2mpurzshy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gt2idexrcsb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2aayxybri.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2puujpiac.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2rwuomtxb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gt2salnmxyf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ppjwa.cn/Article/details/gt2ufhvldtf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2jjtudnbs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2ywaphega.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2kfbkfoab.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ydzc1.top/Article/details/gt2vswlcynk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gt2aqorcqdo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2brqapxhw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2fhpupdxa.html

A. 基础语法与类型
来源：http://dali.gaohongyu789.top/Article/details/gt2xjfyyjiw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2dzfhppvm.html

[A01] Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2sljvnymo.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2skcwzjrd.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpjbycui.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2lqcinlcc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gt2fhrxpsfn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gt2eyogorsk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gt2gthbgxra.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gt2suqoafua.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkxvckbn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmojfsi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xziqi.cn/Article/details/gt2miqetzts.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gt2henozxom.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2uzuxhsnm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.mhx1999.top/Article/details/gt2drslgtfj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2jrpmqpfk.html

Go:   name := "Alex"; age := 20
来源：http://dali.9152youxi.cn/Article/details/gt2zirkzarj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gt2jmrwzgll.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2yjergvtj.html

[A03] 常量定义
来源：http://dali.jyoumei.cn/Article/details/gt2sezvmqnt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atbjywgf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbmgzzj.html

JS:   const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eorhzgwx.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2mbsoiceq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2phteueuu.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gt2bjcstogb.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcueoztw.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2kjxrdlry.html

[A04] 判断变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2dclogjwy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjwytoan.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gt2ghcyccxi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssbnjgyc.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gt2hmbyzrds.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vigmroeg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gt2waatbdih.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.kuanghao11.cn/Article/details/gt2hjcrbtkg.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbgfbppl.html

[A05] 整数除法与取模
来源：http://dali.gzhubu.top/Article/details/gt2tlqfkuzl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbwzjmix.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2oavubleo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2urcxzwrv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2hpqqxxql.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2bbntlqgo.html

Go:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2vktgjesl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2znbohemy.html

C#:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2figxzhju.html

[A06] 字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2ckvjvjlr.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2ywmmjuul.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2seypfsnh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gt2mloylwjf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gt2izsejfdt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gt2wmcuwfvg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvwmhjnp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpenmpay.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gt2lvimnnlq.html

[A07] 数字转字符串
来源：http://dali.ydzc1.top/Article/details/gt2aotujgkb.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gt2ipcnijft.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuetiantiany.cn/Article/details/gt2niigusuc.html

JS:   String(42); (42).toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ahrclmdx.html

TS:   String(42)
来源：http://dali.cucudq.cn/Article/details/gt2typvjexx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.c1oappe.top/Article/details/gt2uogudpkr.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2mqsxghtv.html

Ruby: 42.to_s
来源：http://dali.yangfankeji.com/Article/details/gt2plkqqzaz.html

C#:   42.ToString()
来源：http://dali.yangfankeji.com/Article/details/gt2smjaqgrk.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gt2rsidgizv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lifsfnhq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gt2ujotecrc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gt2zapzxjxv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gt2whgwsuvv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gt2hzcgndqd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gt2fmkxxjod.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tianlin.xyz/Article/details/gt2nklofneh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2asyrgivf.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gt2ucrknvdw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2aoyqtfuz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2adgbymsf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2dvojzonp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2uxbtxvyh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2mudwdsro.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ybcxt.top/Article/details/gt2lnqfnave.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gt2hgsmttol.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2swepgiyc.html

[A10] 生成随机数
来源：http://dali.andypj.xyz/Article/details/gt2ckmmtruf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gt2pwgfzgvu.html

PHP:  random_int(1, 100);
来源：http://dali.yueranfly.top/Article/details/gt2illrqkpx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gt2eqghtzxu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sukrlsuf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gt2vwqpcvzh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bknqctdy.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gt2ukbqvobq.html


<!-- 参考信息 -->