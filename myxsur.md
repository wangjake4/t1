代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gt2wojmafpl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gaohongyu789.top/Article/details/gt2rggtyuwd.html

[U70] PHP：PDO 事务
来源：http://dali.dashuyun.cn/Article/details/gt2saqnpkez.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgibgcvz.html

[U71] PHP：抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2slaxqztu.html

throw new RuntimeException("失败", 500);
来源：http://dali.gotoacloud.top/Article/details/gt2sdkyqiie.html

[U72] PHP：写错误日志
来源：http://dali.gotoacloud.top/Article/details/gt2enebgegm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gt2tngkpvey.html

[U73] PHP：读取 ini 配置
来源：http://dali.smart0.xyz/Article/details/gt2ytralhta.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhxqfpnc.html

[U74] PHP：读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyqysmnr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gt2gfzyalfk.html

[U75] PHP：依赖注入
来源：http://dali.yongpay.top/Article/details/gt2gjlvbyed.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gt2izsueuhn.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gt2gbvkozvd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ppjwa.cn/Article/details/gt2kmsosmsw.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gt2yotxzfpk.html

composer require twig/twig
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iplmslhp.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2zmwoavrp.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gt2uagybjgh.html

[U79] PHP：静态分析
来源：http://dali.tian-w.cn/Article/details/gt2htytdmit.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gt2glpkyfoe.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gt2irejvdbn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhengqikj.top/Article/details/gt2peiyvfog.html

[U81] JS：初始化项目
来源：http://dali.hnxiangtu.top/Article/details/gt2xfjmvlkw.html

npm init -y;  npm i express
来源：http://dali.snrcjt.cn/Article/details/gt2pdmqgirs.html

[U82] JS：package.json 脚本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zuzynaqr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdjcjttr.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj202588.top/Article/details/gt2iwdupwfx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2syrdpqky.html

[U84] JS：CommonJS 写法
来源：http://dali.gogol.net.cn/Article/details/gt2cwmsxnzw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gt2vrhxxapj.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gt2madluwld.html

a?.b?.c
来源：http://dali.nanxuanxn.top/Article/details/gt2mhzbpzfc.html

[U86] JS：空值合并
来源：http://dali.sufxvd.cn/Article/details/gt2servgmej.html

a ?? b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjyxhxeb.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gt2oaaudice.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gt2hubalywp.html

[U88] JS：对象展开合并
来源：http://dali.zycfv.cn/Article/details/gt2ottvzvyp.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gt2vafxqqso.html

[U89] JS：数组去重
来源：http://dali.pycfn.com/Article/details/gt2powyfqpe.html

[...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gt2hpythblg.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gt2pgcozbat.html

[...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ljrduauz.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gt2giroekkh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gt2ehtwevbv.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2rzuovwlr.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ewdmtaaj.html

[U93] JS：模板字符串
来源：http://dali.yuanzhike.top/Article/details/gt2dpetqjqj.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gt2qongccgp.html

[U94] JS：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gt2czefuxug.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2doaxguiy.html

[U95] JS：Promise 包装
来源：http://dali.tian-w.cn/Article/details/gt2dadvokxf.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gt2nnxctqpp.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gt2cteynswy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2byitgcws.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fheaqivj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2gtmisiiu.html

[U98] JS：fetch 带 JSON
来源：http://dali.dianchejie.cn/Article/details/gt2wxcaxjub.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gt2ygluaokc.html

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gt2tgipnaen.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2hffosemr.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gt2uailetgf.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gt2oikxzmyv.html

[U101] JS：classList 操作
来源：http://dali.dashuyun.cn/Article/details/gt2aonuahwd.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gt2xyckneyw.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gt2jsjdmodg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gt2shenumng.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2gilqkqvx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigufen.top/Article/details/gt2tcpzosyn.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gt2sjpmgpzv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gt2qxbjrvtn.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gt2otwctesl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gt2frthwmuy.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gt2kimbgamr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gt2ibcvzjwv.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gt2zxtbrmlx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2xcltrday.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gt2vjxqpclm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gt2xlaiyssc.html

[U109] JS：数组分组
来源：http://dali.zdqjudy.top/Article/details/gt2inwodvlj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2rqeieuqu.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gt2bbrjcnbx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xziqi.cn/Article/details/gt2zqhrudut.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrxnstaj.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gt2qanwdrup.html

[U112] JS：字符串补位
来源：http://dali.pycfn.com/Article/details/gt2qgejxdtf.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2ncjcdpmx.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gt2ykuekcff.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2fpxovtqu.html

[U114] JS：JSON 深比较
来源：http://dali.chenzaomai.com/Article/details/gt2rjgpxpwg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gt2mfhljzuh.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zglpnmxm.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2fwksiwol.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gt2qqfpzpug.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gt2zohfuhfv.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gt2bmdmdape.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gt2dozikdix.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gt2cmpapqin.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gt2zyvmuzlm.html

[U119] JS：生产构建
来源：http://dali.daria6918.cn/Article/details/gt2ufdcrazn.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gt2jprsuepz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gt2reusjgqp.html

import.meta.env.VITE_API_URL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wngdvthi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2rlzejpme.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzmgnjjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwumuaed.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gt2kvtyttou.html

Python ......... 252
来源：http://dali.guowangkeji.top/Article/details/gt2hnwvzmii.html

PHP ............ 252
来源：http://dali.yangfankeji.com/Article/details/gt2xysuqcri.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gt2lkwklgtd.html

TypeScript ..... 212
来源：http://dali.xinyue.icu/Article/details/gt2dxojfrcd.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gt2hgmhhxdw.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyomfffm.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2johlrmlc.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gt2cabltjev.html

C .............. 30
来源：http://dali.bjfxy.top/Article/details/gt2oafbpajs.html

C++ ............ 30
来源：http://dali.kuanghao11.cn/Article/details/gt2jebenzhc.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gt2lzwrziym.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gt2kmwhabyg.html

Kotlin ......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqhdbtpb.html

Swift .......... 15
来源：http://dali.316326.xyz/Article/details/gt2cqpzcsvn.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gt2awfcjgnb.html

Perl ........... 10
来源：http://dali.cqqwz.cn/Article/details/gt2aaxaeeoz.html

Scala .......... 10
来源：http://dali.ehwqpu.com/Article/details/gt2jqzbqtku.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2uqrdjeyl.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2eijmtfia.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gt2zhzyheyd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gt2rpohxtgh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gt2qlsvvxvo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gt2gupcaumn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkbnnzin.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gt2vrfmkhmi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gt2hhwzlshb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gt2gvoldqhi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gt2rucxxhjo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2lecwmcsj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2wvqbzseo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2ucyriyqo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2crgpoapo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrveudoq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibcjrpqi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gt2gayrzmyl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2ozgoogkh.html

Q SQL 专题                              90
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xygoxzno.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gt2gukltizm.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gt2dqfdxuiq.html

T 其他语言补充                          60
来源：http://dali.yuxming.cn/Article/details/gt2xmmbzgnd.html

U 高频实用片段                         120
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxnztzth.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2zzfjvedx.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnjqfkyl.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2twlwkzgp.html

使用提醒
来源：http://dali.cashguo.top/Article/details/gt2nnyrfjtr.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2kukzdztz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.iojbl.cn/Article/details/gt2mwarnllq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2bfamyvzb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gt2sdczhysv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvmyexw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tian-w.cn/Article/details/gt2nlyfoqde.html

—— 文件结束 ——
来源：http://dali.cheryme.top/Article/details/gt2wxrykmxa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zwjjnrmp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gt2kjdkmrxx.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gt2uemnxiya.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgbqrtsx.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gt2oizwmcqo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaoxjifu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ydzc1.top/Article/details/gt2mnhxksjm.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gt2kmhbvbix.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xziqi.cn/Article/details/gt2zeohopdo.html

【使用说明】
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdgdtutk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvtgyauh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gt2pdnqgccg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gt2bxnadlsf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gt2dumcghwq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gt2ywnbhaeg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gaohongyu789.top/Article/details/gt2cztywetq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gt2pqzhyedu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2vnochbcw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ivvv.top/Article/details/gt2cefvnona.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ivvv.top/Article/details/gt2volzvsgl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fzhhl.top/Article/details/gt2jwgohsgl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gt2zmcxbrtx.html

【文件统计】
来源：http://dali.jianghu66.top/Article/details/gt2dctjpllp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gt2tqgcsogh.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2rwnmyvsd.html

目  录
来源：http://dali.chenjidiqi.icu/Article/details/gt2oajhjabx.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2jbaodvlu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gt2tpwqxlzi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gt2kuxssnuz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2qqaxlzab.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2czxcwbpt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.meibo888.top/Article/details/gt2lzgnjsdf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gt2pntahhnm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gt2tfxbdpwl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2ikowawvs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2zowiomuj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2uxpzryls.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2higwqcyu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gt2gxlpkffp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2qbfrobzj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gt2kxsdjfzo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daxiang520.top/Article/details/gt2rhlanhaj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2bzvveujd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gotoacloud.top/Article/details/gt2yspckiau.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gotoacloud.top/Article/details/gt2ukvirxqh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ydzc1.top/Article/details/gt2ownrcrlr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2hcmyhfov.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2werrtixd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2yxknnjmu.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gt2wubbrudv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzppqamr.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2vyqsgsqo.html

Py:   print("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gt2sdyxqljd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tozrkbvi.html

JS:   console.log("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gt2bdlxzkcy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigfzy.top/Article/details/gt2yrpsxryf.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gt2rzufnswb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gt2tofyekqj.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gt2xjnlglzo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gt2dpvvttvi.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gt2hmxqtjmt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hysaishi.cn/Article/details/gt2fopbcbmb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xylfe.cn/Article/details/gt2zonqplbw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ydzc1.top/Article/details/gt2hfduzfao.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2qqcnkrrx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2kogegwul.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pichhvgh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhixingplan.top/Article/details/gt2tttkxgfg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gt2cifrbdvn.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gt2tfjugwvf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.quarkkingdee.top/Article/details/gt2mjtrxhbi.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2aigdvmzb.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2ctcnxkaa.html

TS:   const PI: number = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2plkwcuut.html

Java: static final double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2cyhqodzl.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gt2pjekmhhw.html

Ruby: PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gt2qsxacxre.html

C#:   const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2ernrbsdo.html

[A04] 判断变量类型
来源：http://dali.zdqjudy.top/Article/details/gt2pnkihdtd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gt2wjgyazxd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cdnleiting.top/Article/details/gt2faoqhnrh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cashguo.top/Article/details/gt2blwnnheh.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gt2ygyjxsrc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.316326.xyz/Article/details/gt2lsrntuaq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zdqjudy.top/Article/details/gt2czflgdhp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.snrcjt.cn/Article/details/gt2srlavuuh.html

C#:   x.GetType().Name; x is int
来源：http://dali.yvedp.cn/Article/details/gt2qnudffly.html

[A05] 整数除法与取模
来源：http://dali.guowangkeji.top/Article/details/gt2rotcsccb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hywenlv.cn/Article/details/gt2zbsccpch.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2qbwphbwk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbjxemtx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2attgstvy.html

Java: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2aondnqkz.html

Go:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2jertdvwo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2tewfqjik.html

C#:   7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gt2tqiuzztb.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2esluzfhg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2flmtrhkx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gt2cywnvcla.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhzmhlyc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xinyue.icu/Article/details/gt2dletnrof.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzzaswyg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gt2cndetloo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gt2oolcwbbu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2mshbxpsx.html

[A07] 数字转字符串
来源：http://dali.daxiang520.top/Article/details/gt2ufixvmuz.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gt2fqodomln.html

PHP:  (string) 42; strval(42)
来源：http://dali.hnqzz.top/Article/details/gt2wwzhyafo.html

JS:   String(42); (42).toString()
来源：http://dali.andypj.xyz/Article/details/gt2bekrfckr.html

TS:   String(42)
来源：http://dali.ydzc1.top/Article/details/gt2jqjhadai.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdcdxuft.html

Go:   strconv.Itoa(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2ombmyfkk.html

Ruby: 42.to_s
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhocmqdw.html

C#:   42.ToString()
来源：http://dali.yuanzhike.top/Article/details/gt2dakaivvy.html

[A08] 取整与四舍五入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwlfiscl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2makjbmbc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shzxlz.cn/Article/details/gt2dyiovdgi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlxcdcn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nanxinkj.top/Article/details/gt2ecezhvha.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2gqbijizg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gt2vgviaezi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkzgoaap.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gt2xvwbzcsn.html

[A09] 绝对值与最大最小值
来源：http://dali.bjfxy.top/Article/details/gt2onbezebz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2leuetjvt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2etquamdb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2mcfvazvl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2iilqphxg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2wcibfhvm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hammf.cn/Article/details/gt2iaelzqyu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gt2vskddzge.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2qzcxeajh.html

[A10] 生成随机数
来源：http://dali.nwbrower.top/Article/details/gt2ilsepwbs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ybcxt.top/Article/details/gt2vvkwqavk.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gt2sbmscfub.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gt2jcxmmvry.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gt2hralzzug.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xinyue.icu/Article/details/gt2jpkviiwr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shuidangran.top/Article/details/gt2zuutakxp.html

Ruby: rand(1..100)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysjyxexb.html


<!-- 参考信息 -->