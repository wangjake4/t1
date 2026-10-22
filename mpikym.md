代发 wailian999

[U65] PHP：会话
来源：http://dali.redwolf501.top/Article/details/gt2aldybvzf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2eujatfcs.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gt2sutilwvf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hammf.cn/Article/details/gt2zezyjcqb.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gt2lgaurmxh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gt2useqgbfu.html

[U68] PHP：PDO 连接
来源：http://dali.gogol.net.cn/Article/details/gt2hesnkbfy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gt2klfljwsv.html

[U69] PHP：PDO 预处理
来源：http://dali.xylfe.cn/Article/details/gt2mrwwzokr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gt2ibmhlhwc.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gt2wymuocml.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xziqi.cn/Article/details/gt2gtdvreau.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2llupoole.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gt2fdwkvehl.html

[U72] PHP：写错误日志
来源：http://dali.aibaodan.cn/Article/details/gt2qtvfdosl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gt2xevgtgcd.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gt2vqtltxtf.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gt2ojoqyuiv.html

[U74] PHP：读取环境变量
来源：http://dali.pycfn.com/Article/details/gt2ehqixows.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gt2uggumvna.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsuftgle.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gt2bxwesnzw.html

[U76] PHP：简单路由
来源：http://dali.ybcxt.top/Article/details/gt2iqycsoaz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gt2jlhvwfor.html

[U77] PHP：模板渲染
来源：http://dali.yangfankeji.com/Article/details/gt2lxusxqhe.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gt2ylwsarhe.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gt2ahnpbugp.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gt2oaiakyah.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upetjjgy.html

composer require --dev phpstan/phpstan
来源：http://dali.cheryme.top/Article/details/gt2xezntwdp.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtpnztui.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258888.top/Article/details/gt2wvluipia.html

[U81] JS：初始化项目
来源：http://dali.iojbl.cn/Article/details/gt2hbyffpyd.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gt2bcbbhgxr.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gt2piculqrc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gt2rgkrzcae.html

[U83] JS：ES Module 导入导出
来源：http://dali.iojbl.cn/Article/details/gt2pbhtmeys.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgudvzcw.html

[U84] JS：CommonJS 写法
来源：http://dali.dashuyun.cn/Article/details/gt2pvnstmit.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gzhubu.top/Article/details/gt2revqjkdn.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gt2ffgacnva.html

a?.b?.c
来源：http://dali.daxiang520.top/Article/details/gt2nuhvbscc.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gt2mvyqbxxp.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gt2jymzocdg.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2zhpljcje.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gt2kzifhddp.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gt2slwrgots.html

{ ...a, ...b }
来源：http://dali.cucudq.cn/Article/details/gt2qhxzkmpe.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gt2zggzekdh.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2rxeexxev.html

[U90] JS：数字数组排序
来源：http://dali.chenzaomai.com/Article/details/gt2gxdzwxie.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2dndhplba.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gt2iejfokfj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gt2yqftfghw.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2xuvbznkr.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2uclhtnyt.html

[U93] JS：模板字符串
来源：http://dali.smart0.xyz/Article/details/gt2liloadiz.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gt2sxdwkogx.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2qlperxok.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2dlsuzlcp.html

[U95] JS：Promise 包装
来源：http://dali.gogol.net.cn/Article/details/gt2izfdqfoi.html

new Promise((resolve, reject) => {})
来源：http://dali.jlsjyb.cn/Article/details/gt2ovhmxcyi.html

[U96] JS：async/await 与异常
来源：http://dali.hnqzz.top/Article/details/gt2nsjfaeko.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2libpigva.html

[U97] JS：并发请求
来源：http://dali.sxryk.cn/Article/details/gt2etxtbuqw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2dykwbrbj.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2pdpebobs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gt2bayerspk.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gt2hvwvcqfh.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2ehcqbnyg.html

[U100] JS：DOM 查询
来源：http://dali.ybcxt.top/Article/details/gt2xrxkpsgc.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gt2midbtcqf.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gt2gghkzpfb.html

el.classList.toggle("active")
来源：http://dali.c1oappe.top/Article/details/gt2uvtrbngr.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gt2qephobqe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gt2pawvcjsx.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gt2heqrcttt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gt2gfvmasjt.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gt2dqwlpjzy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2knatvuso.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gt2eorebrot.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gt2yxlaylnq.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2qkvxdufg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtqeysxp.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gt2krxndecs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eoenjgtj.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gt2dspsmknh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gt2wjzgamio.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gt2wonranzk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gt2ddhfgvwy.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gt2newgkslj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gt2vrintmbk.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gt2uculnhvc.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gt2erhdqiva.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gt2hyqxtbfm.html

"7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2kvyxqbni.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gt2zsjwbugu.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2qelmhrac.html

[U114] JS：JSON 深比较
来源：http://dali.jianghu66.top/Article/details/gt2gzfvnjri.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2diwdgvhv.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2cekugjuu.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2jrrrahaz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhixingplan.top/Article/details/gt2txchqxdb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gt2whqexjdc.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2ycbmxcyz.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gt2bocudzmq.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gt2epxbjbih.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gt2kpaydamj.html

[U119] JS：生产构建
来源：http://dali.jinqigufen.top/Article/details/gt2bjwilqtf.html

npx vite build
来源：http://dali.hnxiangtu.top/Article/details/gt2xjdlahup.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gt2ogjwhzoi.html

import.meta.env.VITE_API_URL
来源：http://dali.chenlongwang.top/Article/details/gt2lsalsxdz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtcdcrqn.html

统计汇总
来源：http://dali.xinyue.icu/Article/details/gt2cvytgkcz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2nbtwwmiq.html

按语言统计（条）：
来源：http://dali.c1oappe.top/Article/details/gt2kezzegzd.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gt2gepvqkxo.html

PHP ............ 252
来源：http://dali.cqqwz.cn/Article/details/gt2rktnwobq.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gt2tbvrmdxg.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvgygyom.html

Java ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2caeeuspf.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2vmxkvagf.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gt2sxlyhyzf.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gt2cduuipat.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtvlsete.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csmgrmwn.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gt2xqfolhwl.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gt2nqzqggdn.html

Kotlin ......... 15
来源：http://dali.hywenlv.cn/Article/details/gt2nauebgnc.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gt2oszjhfqs.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yuiuqaic.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gt2xpkskvza.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrhwggp.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2xhgqyfyc.html

合计 ........... 2106 条
来源：http://dali.gotoacloud.top/Article/details/gt2rawyadmf.html

按章节统计：
来源：http://dali.tian-w.cn/Article/details/gt2ibiuxqzd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2jwaqaffq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2brxibgrr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ksncxexm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2oivwgoms.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258888.top/Article/details/gt2xitqehlm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gt2kmglabdy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gt2mnmmzwak.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2erierozl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwankddl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2nbbmnkol.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2uuzywjpx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2eliekojy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2tznvihca.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2rcjecogo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gogol.net.cn/Article/details/gt2ruyiglsq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2namtaphf.html

Q SQL 专题                              90
来源：http://dali.wangdashe.top/Article/details/gt2xezckooj.html

R Bash 专题                             80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxwjfubg.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gt2ubateyti.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gt2ihbvtxqn.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gt2hczvpokx.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2wjbstilb.html

合计                                  2106 条
来源：http://dali.xinyue.icu/Article/details/gt2klogrtca.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2ptaievap.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gt2qxqqxhzb.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2yszhtswe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gt2stmbkbxf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gt2aobuhgcm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hammf.cn/Article/details/gt2fjlezvea.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gt2bqxbowxs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xziqi.cn/Article/details/gt2lnilhixr.html

—— 文件结束 ——
来源：http://dali.gogol.net.cn/Article/details/gt2rmqjhfcf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ooubzidf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gt2ldizyibc.html

Common Programming Examples Cheat Book
来源：http://dali.0kj1m.cn/Article/details/gt2yswqzapq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2civukter.html

【收录内容】
来源：http://dali.hfpthk.cn/Article/details/gt2kuzyeasf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhongyouzk.top/Article/details/gt2yspncgej.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcnazurh.html

SQL · Bash · C · C++
来源：http://dali.ppjwa.cn/Article/details/gt2vzpixstz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnqzz.top/Article/details/gt2hvxkytjl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyydxpg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hywenlv.cn/Article/details/gt2ttlgfsmi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuxming.cn/Article/details/gt2fwrqfkkr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gt2vgeiqqlg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cashguo.top/Article/details/gt2hosmzrpw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yueranfly.top/Article/details/gt2ysfmspfv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sxryk.cn/Article/details/gt2ogkbhhbt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgufenzy.top/Article/details/gt2gzbfighp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.bjfxy.top/Article/details/gt2tkjkzbgo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cqqwz.cn/Article/details/gt2brfjyulb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zycfv.cn/Article/details/gt2yjyvvdxq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gt2acnzcroc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gt2bszxdnef.html

【文件统计】
来源：http://dali.chenzaomai.com/Article/details/gt2bztnixuw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gt2ngvgmxia.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2ajsirscq.html

目  录
来源：http://dali.pycfn.com/Article/details/gt2wlixeywa.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2hrvkledk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gt2pxaskxdy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gt2kssbeyay.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gt2vrelhcrs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gt2bzypupcn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gt2zyvsvnqz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gt2srpaimcs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2rxveqkxr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2brrknzfi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gt2itgfaozm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gt2diwkzjti.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2odlrukrq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2kgziiucf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttpgtntw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gt2aqxfywhr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.meibo888.top/Article/details/gt2fyelwxek.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2sdqkdbem.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2acjqkzme.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2htqwhpox.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2uezjbhus.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gt2uvmjoaym.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2pcxouqpz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jikxiuzw.html

A. 基础语法与类型
来源：http://dali.gotoacloud.top/Article/details/gt2ofzmxdxt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ixpyrkmu.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2kumnfbuf.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2jwsapsxt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gt2ljsaoimy.html

JS:   console.log("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2cuwoqkre.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tanke756.top/Article/details/gt2athurapz.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2tjqbhbsr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejgoxwtr.html

Ruby: puts "Hello, World!"
来源：http://dali.guowangkeji.top/Article/details/gt2yjjoushw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2zjxtqwjm.html

[A02] 变量声明与赋值
来源：http://dali.zhoulong.xyz/Article/details/gt2kbbykekt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gzhubu.top/Article/details/gt2szrwirtg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gt2xwkjctkt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2uxwqjvmt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbtwzxvz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2lshwdmjx.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gt2ogjhemlu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aizwys.cn/Article/details/gt2wnniakdi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgbstswo.html

[A03] 常量定义
来源：http://dali.quarkkingdee.top/Article/details/gt2zbyvavys.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpaqjcne.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2mccgwmco.html

JS:   const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2lrjrmwxd.html

TS:   const PI: number = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2aujashzp.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2ieeimefc.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndqwqtft.html

Ruby: PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gt2gfpjxksb.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2gempocee.html

[A04] 判断变量类型
来源：http://dali.yj202588.top/Article/details/gt2ypnydmfx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.9152youxi.cn/Article/details/gt2wpgmevuy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cheryme.top/Article/details/gt2ajgrqsol.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gt2fjdagivw.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gt2uhmirnpo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gt2gtbijlhe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gt2dpnpishp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.9152youxi.cn/Article/details/gt2ulfstfgk.html

C#:   x.GetType().Name; x is int
来源：http://dali.tanke756.top/Article/details/gt2icolgtvo.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gt2jshpwhyg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gt2duzpbzwf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2ksuzpufy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fckkmfty.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2zlsjshsx.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2uzzfeyyn.html

Go:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2bcronmnd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2pibdoonq.html

C#:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2hbhcdpko.html

[A06] 字符串转数字
来源：http://dali.fengsongda.top/Article/details/gt2oekzetzk.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2xzihzcmr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gotoacloud.top/Article/details/gt2acomrqoo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gt2fvdyzuac.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.316326.xyz/Article/details/gt2tgzlpbta.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txjtkvfb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fzhhl.top/Article/details/gt2ilcrfcue.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.havefunace.top/Article/details/gt2gaxhfmpg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gt2fjgnvcod.html

[A07] 数字转字符串
来源：http://dali.yj20258.top/Article/details/gt2jkugdgrw.html

Py:   str(42)
来源：http://dali.c1oappe.top/Article/details/gt2xhlquewx.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuxming.cn/Article/details/gt2pxbkhxsj.html

JS:   String(42); (42).toString()
来源：http://dali.iojbl.cn/Article/details/gt2xjsmjfyk.html

TS:   String(42)
来源：http://dali.yj20258888.top/Article/details/gt2iwxnowza.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuxming.cn/Article/details/gt2uruhzhjh.html

Go:   strconv.Itoa(42)
来源：http://dali.316326.xyz/Article/details/gt2bthvnwtw.html

Ruby: 42.to_s
来源：http://dali.yuxming.cn/Article/details/gt2swiafrld.html

C#:   42.ToString()
来源：http://dali.hnqzz.top/Article/details/gt2mtgudmhv.html

[A08] 取整与四舍五入
来源：http://dali.ybcxt.top/Article/details/gt2lefnkqcb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gt2ocudkyjj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gt2ajytvgdb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gt2nrspppam.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jlsjyb.cn/Article/details/gt2rvmrjvvy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2uvxdtaps.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gt2ekmvaubc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncbvmrny.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avxjovhy.html

[A09] 绝对值与最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2vczndpzb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2ksvofkzx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2fejwmskc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2otnayynn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2pnqqxbfv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2aacxiuvs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nwbrower.top/Article/details/gt2frpntofv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.birdmap.top/Article/details/gt2rwipivbr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2jvoyefni.html


<!-- 参考信息 -->