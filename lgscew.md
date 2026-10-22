代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.yj202588.top/Article/details/gtufvmxeii.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daxiang520.top/Article/details/gtglcwdveq.html

[U68] PHP：PDO 连接
来源：http://dali.cdnleiting.top/Article/details/gtxjtmujiv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cqqwz.cn/Article/details/gtsyawqtfs.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gtjitrictb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xinyue.icu/Article/details/gtodqwidzf.html

[U70] PHP：PDO 事务
来源：http://dali.zhengqikj.top/Article/details/gtsaxvdgnu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gaohongyu789.top/Article/details/gtlqwdwpie.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtkibaqpxp.html

throw new RuntimeException("失败", 500);
来源：http://dali.ivvv.top/Article/details/gtbpvtfnba.html

[U72] PHP：写错误日志
来源：http://dali.kuanghao11.cn/Article/details/gtgqkhbchi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tanke756.top/Article/details/gtnbuiwism.html

[U73] PHP：读取 ini 配置
来源：http://dali.c1oappe.top/Article/details/gtdmnoaxgr.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gtebsocssc.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtjikutsqq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtkrtzvlup.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtlrbbekeb.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gtjfzzjyvq.html

[U76] PHP：简单路由
来源：http://dali.316326.xyz/Article/details/gtaxfagdmr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jyoumei.cn/Article/details/gtzwymvegw.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gtalpbwmpo.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gtshskhuwp.html

[U78] PHP：单元测试
来源：http://dali.yj202588.top/Article/details/gtxfjvgujh.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gttazneyjv.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gtcokkxoon.html

composer require --dev phpstan/phpstan
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagdfsnsk.html

[U80] PHP：代码规范修复
来源：http://dali.xziqi.cn/Article/details/gtfyhiyqgo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtbwmjglwm.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gthgwoiofd.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gtkxzufmmr.html

[U82] JS：package.json 脚本
来源：http://dali.gaohongyu789.top/Article/details/gtumqwpwbb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtefqulzfh.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gtbofvmvzd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtssaouekt.html

[U84] JS：CommonJS 写法
来源：http://dali.ppjwa.cn/Article/details/gtcdxuaiah.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.kuanghao11.cn/Article/details/gtoymmrjkc.html

[U85] JS：可选链
来源：http://dali.andypj.xyz/Article/details/gtfwmvsiat.html

a?.b?.c
来源：http://dali.yongpay.top/Article/details/gteypjepvt.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gtndgjfsog.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gtetvhzryn.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtdiyeovab.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sufxvd.cn/Article/details/gtyvihahsg.html

[U88] JS：对象展开合并
来源：http://dali.cqqwz.cn/Article/details/gthtzwbcyq.html

{ ...a, ...b }
来源：http://dali.guowangkeji.top/Article/details/gtnwucjcmn.html

[U89] JS：数组去重
来源：http://dali.xinyue.icu/Article/details/gtmbquqycs.html

[...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtqmqyckbb.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gtutrsnokb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtvecmdwyj.html

[U91] JS：对象键值遍历
来源：http://dali.316326.xyz/Article/details/gtrnqnwjxq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenzaomai.com/Article/details/gtaqhkntub.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gthshepyqh.html

structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtnbokapoj.html

[U93] JS：模板字符串
来源：http://dali.dashuyun.cn/Article/details/gtyyhqtwsi.html

`共 ${n} 条`
来源：http://dali.xuetiantiany.cn/Article/details/gtjajtirxw.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtmdwaeiac.html

const double = x => x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxsnqmfy.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gtdbcdrmih.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gtxpphcrav.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gtighofppf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnsrrdux.html

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gtlethvcvu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtdasseane.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuxming.cn/Article/details/gtdcrptvar.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cdnleiting.top/Article/details/gtjmuyxnwu.html

[U99] JS：事件监听
来源：http://dali.tian-w.cn/Article/details/gtfesyhumj.html

el.addEventListener("click", e => {})
来源：http://dali.ydzc1.top/Article/details/gtkspvpmit.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtxdbgzhbz.html

document.querySelector(".item")
来源：http://dali.cashguo.top/Article/details/gtwajbflwt.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gttpaodcen.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtlvbqnyti.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gttlvpkrcj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gtytknmker.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtumzguscp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gtchltogci.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gtmsexixfc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtzyhzhgaa.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeexwfym.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtevsikiyg.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gtqoxlzdal.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gtghdoeqwn.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gttwrbaehs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtupfseryw.html

[U108] JS：随机整数
来源：http://dali.xuanzx.com/Article/details/gthjzicdbs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nwbrower.top/Article/details/gtfbcqvoja.html

[U109] JS：数组分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatzdqthr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtlxvylehz.html

[U110] JS：数组分块
来源：http://dali.xziqi.cn/Article/details/gtwnlcovwe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtivldpxrg.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gtsyskdgqz.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gtcttiixkr.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gtsusdnbrw.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtjehuhaqi.html

[U113] JS：正则替换全部
来源：http://dali.yvedp.cn/Article/details/gtygbeoalb.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyrdqddr.html

[U114] JS：JSON 深比较
来源：http://dali.feifeiyinyue.top/Article/details/gtuuxhifse.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtskwurbbu.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtclcuyjym.html

crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtxmlabzfk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gtjjecbogr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cqqwz.cn/Article/details/gtdbvgewzd.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtagvviilu.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtdvmbafzo.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gthagkhrlf.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gtvitmfapa.html

[U119] JS：生产构建
来源：http://dali.0kj1m.cn/Article/details/gtcmhcchzy.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtwobbxdjp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gtejvppatw.html

import.meta.env.VITE_API_URL
来源：http://dali.bjfxy.top/Article/details/gtxlbveaeh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfdmdcgei.html

统计汇总
来源：http://dali.sufxvd.cn/Article/details/gtpsalwlyy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtavsnurej.html

按语言统计（条）：
来源：http://dali.daria6918.cn/Article/details/gtczjjcdhf.html

Python ......... 252
来源：http://dali.cashguo.top/Article/details/gthcbftszw.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gtpykhenju.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gtnbuepccw.html

TypeScript ..... 212
来源：http://dali.9152youxi.cn/Article/details/gtpyhiybqr.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtdrbrujyf.html

Go ............. 212
来源：http://dali.sweek.top/Article/details/gtasnivcvz.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtghfqlbsf.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtppyqgabc.html

C .............. 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgixwmcx.html

C++ ............ 30
来源：http://dali.snrcjt.cn/Article/details/gtcsrbqkpx.html

SQL ............ 90
来源：http://dali.chenjidiqi.icu/Article/details/gtcuoplzot.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gthmjszfba.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gttflinjsf.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gtqetkkqpo.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gtxeczgolq.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtzstuidsm.html

Scala .......... 10
来源：http://dali.zhoulong.xyz/Article/details/gthqqyjmyr.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gttdlwztju.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtxxsqitiu.html

按章节统计：
来源：http://dali.gotoacloud.top/Article/details/gtoryhfoob.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gtuxqiyfcg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gticpjlrcp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtaboznadr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gtareazthq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gtbevgxjdz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprmzirie.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtkjgdewpt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtrcejcoba.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtsjlsdywq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtdjwkshcc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtzrvyttui.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtpmyrrnjo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtlgefxfiq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtwllykstn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gtdcqvabva.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtnrbosnom.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gtxwcrotmo.html

R Bash 专题                             80
来源：http://dali.hywenlv.cn/Article/details/gtxoapfwan.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gtkowwjhnj.html

T 其他语言补充                          60
来源：http://dali.haohaochexian.top/Article/details/gtvxyntcgy.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gtvvmxljjd.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtqyqxxzhc.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtalltxrnp.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gthzrptvxf.html

使用提醒
来源：http://dali.hongshengwenyu.top/Article/details/gttnbzklai.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtamjaldvd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtsjqchdop.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gtrawfnsmk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcofwbrm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gtpdsohwrj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtziythadw.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gtowcbwndq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdffabhyu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gtydhmahnt.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gtnbceffgo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrbheesgm.html

【收录内容】
来源：http://dali.hnqzz.top/Article/details/gtifuvnhbz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gtvsohppbz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pycfn.com/Article/details/gtkhczyqwc.html

SQL · Bash · C · C++
来源：http://dali.ydzc1.top/Article/details/gtxagighnt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gtyyeirdjk.html

【使用说明】
来源：http://dali.jianghu66.top/Article/details/gtnluttqyz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtgrbjqgbw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtydwwoqfr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yueranfly.top/Article/details/gtmksumhlq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cqqwz.cn/Article/details/gtptmyqfsj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cqqwz.cn/Article/details/gtpcicgrbv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dashuyun.cn/Article/details/gtnobnlyjx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigufen.top/Article/details/gtspuurmeq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.snrcjt.cn/Article/details/gtymyyweok.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigufen.top/Article/details/gtqjlzyktv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yueranfly.top/Article/details/gtkbucglkq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtygkvslfi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gtnklnjibg.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gtdfxcibax.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tian-w.cn/Article/details/gtzionfeml.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtkcmfevmb.html

目  录
来源：http://dali.zdqjudy.top/Article/details/gttppqmvyq.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtnemvcuai.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gtickqsaft.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtkcmwobul.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtdsmmgblu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gttiiiclge.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.iojbl.cn/Article/details/gtrbvmzptw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gtazwezfzt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtfzmqeuwz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtqozbsbwi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gthqyjpvzp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtiyoahczs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtgppbshpr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtwpaedbxa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtslhitkyy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtjxaruw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.9152youxi.cn/Article/details/gtinuddzzp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtgpfnfept.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gtpnwapywe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.mhx1999.top/Article/details/gtxkaxnilp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xylfe.cn/Article/details/gtxqtqwzhf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtugjxmnjw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtddergiuk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgscftmte.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gttzkkydeo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwbezozz.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gtnuqbvnmd.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gthciuhvgw.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gtnagmpryn.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtgaomnzdn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yvedp.cn/Article/details/gtusufypqu.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtminedrsv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtrzwaxgbr.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gtebpesdmu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtzwhuhwmf.html

[A02] 变量声明与赋值
来源：http://dali.jqgufenzy.top/Article/details/gtfqbpqaht.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtymojemnr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gtlyldhmwb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ydzc1.top/Article/details/gtefhbymim.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtllleewwt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtwmbzuvsl.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gtwvksphgj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gtfbmvgdkw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtchddlbxq.html

[A03] 常量定义
来源：http://dali.nwbrower.top/Article/details/gtlgzmexfm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cucudq.cn/Article/details/gtndcedphx.html

PHP:  const PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtacnpkgnw.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthviduigh.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzvmbqjr.html

Java: static final double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtgtopzehh.html

Go:   const PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gtpobxhfxa.html

Ruby: PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gtpmvrmdvl.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtqqjvxwbo.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gtdgynumme.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sweek.top/Article/details/gtwmcjuvnq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhixingplan.top/Article/details/gtydcraijh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjcqhkyl.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtyzqgznhg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnbzwndu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gtyjscvktx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenlongwang.top/Article/details/gtgkvoymes.html

C#:   x.GetType().Name; x is int
来源：http://dali.yvedp.cn/Article/details/gtozybhpoz.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gtbftyaahg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hammf.cn/Article/details/gtqncbrhtw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtfkuosobt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtzxuyjzaj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtbgojwvlp.html

Java: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtqfhbhzty.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtcwrjvwrz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtiqigzfpz.html

C#:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtqkxrumtb.html

[A06] 字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwdqlhxu.html

Py:   int("42"); float("3.14")
来源：http://dali.smart0.xyz/Article/details/gtqwhdswht.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guannengcc.top/Article/details/gtnlzkrram.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtygnyerxq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtpjmgskol.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtdjgidcpt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dashuyun.cn/Article/details/gtnzyizekb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gtlnygawoc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.havefunace.top/Article/details/gtvqfbwhbj.html

[A07] 数字转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtupghzwuj.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtnzoruohv.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigfzy.top/Article/details/gtxmtoqrtt.html

JS:   String(42); (42).toString()
来源：http://dali.zdqjudy.top/Article/details/gtmafbshez.html

TS:   String(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtavythcwo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gtkuidjcek.html

Go:   strconv.Itoa(42)
来源：http://dali.havefunace.top/Article/details/gtvfslrcis.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gtgrjggviw.html

C#:   42.ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtigmocksl.html

[A08] 取整与四舍五入
来源：http://dali.pycfn.com/Article/details/gtqkjaqpuf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtigflqvwr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.birdmap.top/Article/details/gtkjdgjyoc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtjdpobofq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.havefunace.top/Article/details/gttginfyct.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtirxxkbae.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtmkwugqfr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zdqjudy.top/Article/details/gthpuaeluo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtfbfxbiit.html

[A09] 绝对值与最大最小值
来源：http://dali.cashguo.top/Article/details/gtdvcllxka.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtkiqiykeo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtmcpwbaul.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtbwnbqwxt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtnpgmunhc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtghcuiklq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnqzz.top/Article/details/gtwskwykmv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gtonrimqgy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtagwbiplt.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtmhrahojo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shangyingyoupin.top/Article/details/gtexwzrfcr.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gtyrvegeoy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtpvdkryxq.html


<!-- 参考信息 -->