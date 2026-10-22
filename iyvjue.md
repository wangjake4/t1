代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.sweek.top/Article/details/gt2msughzpp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.smart0.xyz/Article/details/gt2pghjwdii.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbcyughb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gt2hrgtllho.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuymxxyp.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gt2serojfyz.html

[U72] PHP：写错误日志
来源：http://dali.jqgufenzy.top/Article/details/gt2wufjanzx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xziqi.cn/Article/details/gt2cgxbcmhf.html

[U73] PHP：读取 ini 配置
来源：http://dali.jlsjyb.cn/Article/details/gt2lufkbnxz.html

parse_ini_file("config.ini", true)
来源：http://dali.aibaodan.cn/Article/details/gt2doyfcvrk.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2gxwjphbc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jyoumei.cn/Article/details/gt2ptfmsrun.html

[U75] PHP：依赖注入
来源：http://dali.aibaodan.cn/Article/details/gt2dwkrimid.html

composer require psr/container
来源：http://dali.cdnleiting.top/Article/details/gt2ehipeysg.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moekblzz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jlsjyb.cn/Article/details/gt2koxekgxt.html

[U77] PHP：模板渲染
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwrdsgyv.html

composer require twig/twig
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvpdmbdx.html

[U78] PHP：单元测试
来源：http://dali.ehwqpu.com/Article/details/gt2dwksfxzx.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gt2jkxyenws.html

[U79] PHP：静态分析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lthmgwtv.html

composer require --dev phpstan/phpstan
来源：http://dali.cheryme.top/Article/details/gt2qfoxktcc.html

[U80] PHP：代码规范修复
来源：http://dali.pycfn.com/Article/details/gt2qldbtzrm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.smart0.xyz/Article/details/gt2ordgmavv.html

[U81] JS：初始化项目
来源：http://dali.yanxiufei.cn/Article/details/gt2nvtuurmp.html

npm init -y;  npm i express
来源：http://dali.ppjwa.cn/Article/details/gt2pdammghh.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywasuksu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gt2yhpwugvk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhixingplan.top/Article/details/gt2yyxbcavz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gt2avbpivch.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmcbmloy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shzxlz.cn/Article/details/gt2bivhfqyl.html

[U85] JS：可选链
来源：http://dali.yuanzhike.top/Article/details/gt2odihomwc.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gt2hfawodpp.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqvhguab.html

a ?? b
来源：http://dali.yuanzhike.top/Article/details/gt2oecksecw.html

[U87] JS：解构默认值
来源：http://dali.daria6918.cn/Article/details/gt2mqlayvwe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hfpthk.cn/Article/details/gt2cpvtotxy.html

[U88] JS：对象展开合并
来源：http://dali.gzhubu.top/Article/details/gt2mybmhodm.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gt2tlzqbucp.html

[U89] JS：数组去重
来源：http://dali.birdmap.top/Article/details/gt2hjvnksvx.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2pisgsyej.html

[U90] JS：数字数组排序
来源：http://dali.cheryme.top/Article/details/gt2xcvkzwqu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2lpzrodbn.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2myerwhap.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gt2ljsrilka.html

[U92] JS：深拷贝
来源：http://dali.birdmap.top/Article/details/gt2ibntsgao.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2sdpfmunq.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gt2eyehfkaf.html

`共 ${n} 条`
来源：http://dali.hnxiangtu.top/Article/details/gt2bfrarxes.html

[U94] JS：箭头函数
来源：http://dali.yj202588.top/Article/details/gt2ulhrwqgo.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqatkemb.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gt2oysbsqon.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxuanxn.top/Article/details/gt2iiiyqnga.html

[U96] JS：async/await 与异常
来源：http://dali.sysykeji.top/Article/details/gt2yjnedfek.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2jzbbqmkb.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scclrykp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2nssixkiz.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gt2krmrodhl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gt2buczcwco.html

[U99] JS：事件监听
来源：http://dali.nanxinkj.top/Article/details/gt2gasdldax.html

el.addEventListener("click", e => {})
来源：http://dali.sufxvd.cn/Article/details/gt2linnrxly.html

[U100] JS：DOM 查询
来源：http://dali.mhx1999.top/Article/details/gt2jgthtdwl.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gt2iwlombtf.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gt2trhnmweo.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gt2htwsjpcr.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gt2wqtsyxqv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gt2mbcspdzi.html

[U103] JS：定时器
来源：http://dali.hnxiangtu.top/Article/details/gt2iftyudxz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gt2pxoshccn.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gt2bppmloqm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2jlfbiigz.html

[U105] JS：节流
来源：http://dali.guowangkeji.top/Article/details/gt2ifischwa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxictnus.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gt2oeimhbew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gt2lpsmuzzx.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2ssallwuo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2befqbzpk.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gt2zrzarbwu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.birdmap.top/Article/details/gt2blayjdlj.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gt2whumyygb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwshntjz.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gt2qufsbqag.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptdnhyjj.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gt2ankhqolx.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gt2diaeoszv.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gt2buiilnmp.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2qnemhdnq.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gt2nkcetlen.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2ysusdpua.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gt2xuiwzcpz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2plzftphc.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2knylxxcd.html

crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2imswqcys.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.iojbl.cn/Article/details/gt2mbhqxprd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gt2mrdjsvbc.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gt2xviteeki.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gt2inwihkhe.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gt2heeqqmyq.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gt2akrmifdm.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gt2yvwdrdoe.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gt2uadeijeu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gt2jgtzjlrw.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gt2abxyxwkm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2nrqrycml.html

统计汇总
来源：http://dali.ybcxt.top/Article/details/gt2hjobcdwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eujlshow.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gt2zjxfohuj.html

Python ......... 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2qegxpzud.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gt2andhhhdt.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzizkpci.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gt2lujrmfdm.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gt2prqnlxgx.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gt2qxzwdzeo.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2jyvlfjyk.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2nltwoqkp.html

C .............. 30
来源：http://dali.tianlin.xyz/Article/details/gt2netpmozm.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gt2dnclikrs.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gt2gdlpzndv.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gt2kowqrkvj.html

Kotlin ......... 15
来源：http://dali.hammf.cn/Article/details/gt2rbygoogo.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkrbkego.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gt2unzcnpsk.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gt2kfrctofq.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2vqunksnb.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2kyffnojh.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gt2phutbvbk.html

按章节统计：
来源：http://dali.gotoacloud.top/Article/details/gt2zjrnedtc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcstcceo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2fdvssfwq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnxzxhpa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2itdnbyfh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.snrcjt.cn/Article/details/gt2lsymggpo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gt2vvyyiesx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gt2sdhoxtkh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gt2vxyftset.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrntkljf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2cmelcuut.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2ehyddine.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2twpmcdef.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxhdcahh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gt2bgpzgkua.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daxiang520.top/Article/details/gt2iovcovxi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gt2aegvcfnf.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gt2nekjgbkv.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpdcowoq.html

S C / C++ 专题                          60
来源：http://dali.quarkkingdee.top/Article/details/gt2udrbyhoc.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gt2fvzbrwpv.html

U 高频实用片段                         120
来源：http://dali.jyoumei.cn/Article/details/gt2ulhnppxt.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2srfbqwcs.html

合计                                  2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvdpkaom.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2zytckogb.html

使用提醒
来源：http://dali.hnqzz.top/Article/details/gt2jwxcudpr.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gt2ibcyoied.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.smart0.xyz/Article/details/gt2dyrjcmtj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.0kj1m.cn/Article/details/gt2zrenoghy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gt2oqgmdllx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gt2umtderrw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gt2glggagng.html

—— 文件结束 ——
来源：http://dali.tanke756.top/Article/details/gt2vjatmsws.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ccvxqano.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gt2euhhvujz.html

Common Programming Examples Cheat Book
来源：http://dali.pycfn.com/Article/details/gt2xogtnykr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zsmczljw.html

【收录内容】
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdgurkgw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sufxvd.cn/Article/details/gt2tvleierk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gt2nubcxata.html

SQL · Bash · C · C++
来源：http://dali.jiagoushi.top/Article/details/gt2elojfart.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mroxpbdm.html

【使用说明】
来源：http://dali.snrcjt.cn/Article/details/gt2hzofnhqs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhixingplan.top/Article/details/gt2kinzecqb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhcvaebt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gt2qnzdldae.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aibaodan.cn/Article/details/gt2cjdimjar.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ydzc1.top/Article/details/gt2altgzwcr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yanxiufei.cn/Article/details/gt2saqyuyzx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcmwgslt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2jdfneddp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuanzhike.top/Article/details/gt2spkgsxum.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jlsjyb.cn/Article/details/gt2mjmvwsln.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gt2vrkrtdqs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cheryme.top/Article/details/gt2mmuffckt.html

【文件统计】
来源：http://dali.hysaishi.cn/Article/details/gt2bwasbked.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sufxvd.cn/Article/details/gt2otrzdqog.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2zqjknnbw.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gt2qeedsycx.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2alfxicuz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hfpthk.cn/Article/details/gt2tjgxwkrn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2eauwredg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2tkzgjvlx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2tuxswrho.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zdqjudy.top/Article/details/gt2jjncgylv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gt2prvmvtbg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gt2ffkukivu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gt2ztaeyklp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2hbcodrlu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gt2rewcohjc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2hdmunyrj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2proqqaqg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2vsmeaipo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gt2edgmudjj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gt2qrctxnay.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gt2pnmexbfs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2wpmvfwli.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gt2zfnnjajk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gt2jmtqcoaa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gt2qtlltnrj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkroycpl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2msaalblt.html

A. 基础语法与类型
来源：http://dali.jianghu66.top/Article/details/gt2brlpbloa.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2uuboaizw.html

[A01] Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2tmkhtydz.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwybmrnx.html

PHP:  echo "Hello, World!";
来源：http://dali.hysaishi.cn/Article/details/gt2snlsfruc.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2ometdbzm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gt2pwevgyoa.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gt2dbqhqarc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gt2ushykptu.html

Ruby: puts "Hello, World!"
来源：http://dali.guannengcc.top/Article/details/gt2kmzghufq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2qmaqtpyl.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gt2bcmbafhe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsigtnmo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2bjoexvsy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2posigxjm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htdrryjd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2psfaxnle.html

Go:   name := "Alex"; age := 20
来源：http://dali.hysaishi.cn/Article/details/gt2fbajkcwx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shuidangran.top/Article/details/gt2rdbpoabf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2ltkxylpg.html

[A03] 常量定义
来源：http://dali.jiagoushi.top/Article/details/gt2ejjnxirt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.snrcjt.cn/Article/details/gt2fvotvlrz.html

PHP:  const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2vjcvrpns.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2vvcnhrvb.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2xwtuxrtf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2lzcxzoqm.html

Go:   const PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaycavwj.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gt2cmmyleei.html

C#:   const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2rsugbqlq.html

[A04] 判断变量类型
来源：http://dali.shuidangran.top/Article/details/gt2wlsteors.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daria6918.cn/Article/details/gt2nhvvutyt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnvedlgw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmuhqnec.html

TS:   typeof x; x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2cdifdchu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gt2dtmqgkvn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gt2gilpnegj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fengsongda.top/Article/details/gt2ruftfeph.html

C#:   x.GetType().Name; x is int
来源：http://dali.ydzc1.top/Article/details/gt2kdxnjhid.html

[A05] 整数除法与取模
来源：http://dali.wangdashe.top/Article/details/gt2vocayubo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gotoacloud.top/Article/details/gt2nzrbalek.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2kmyqmkde.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2pcgtdkls.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjiytbfe.html

Java: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2zazdwczl.html

Go:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2fkwxxkue.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2dtiwrfkh.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2pzwzgxlt.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abxbkcxj.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258.top/Article/details/gt2paieupmh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2wqyosbpv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhixingplan.top/Article/details/gt2ifnmbjnt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.smart0.xyz/Article/details/gt2zrhtydvg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gt2vbjhpzlq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pycfn.com/Article/details/gt2abhkttku.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.andypj.xyz/Article/details/gt2mxrihxpr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.bjfxy.top/Article/details/gt2ltuqdpny.html

[A07] 数字转字符串
来源：http://dali.ivvv.top/Article/details/gt2otwawdbq.html

Py:   str(42)
来源：http://dali.xuetiantiany.cn/Article/details/gt2udiycxbi.html

PHP:  (string) 42; strval(42)
来源：http://dali.0kj1m.cn/Article/details/gt2fjetutkb.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gt2bfleyopq.html

TS:   String(42)
来源：http://dali.hysaishi.cn/Article/details/gt2ulsqdypt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gt2llvhrxtl.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gt2wnngvcya.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gt2fdfxnkob.html

C#:   42.ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifolzsvh.html

[A08] 取整与四舍五入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icdyhgnu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2slatppmu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gt2gmbdvltp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2ebeckjfh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sysykeji.top/Article/details/gt2meiwjful.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvjbwfau.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gt2gedghxfy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shzxlz.cn/Article/details/gt2dymqytap.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2nprfxgfr.html

[A09] 绝对值与最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2slptkivw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2lnxdydlo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2lrnfxrne.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecrbyurr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2fuunqgls.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgafzxoh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxuanxn.top/Article/details/gt2ygijygpy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gotoacloud.top/Article/details/gt2vqsrofba.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2unydgntd.html

[A10] 生成随机数
来源：http://dali.aizwys.cn/Article/details/gt2eintjmkf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jiagoushi.top/Article/details/gt2xgkcwdco.html

PHP:  random_int(1, 100);
来源：http://dali.xylfe.cn/Article/details/gt2hcuppcil.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gt2tmoaeqiz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gt2eexdrcek.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vixslpsq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.0kj1m.cn/Article/details/gt2pfowgvwy.html

Ruby: rand(1..100)
来源：http://dali.dashuyun.cn/Article/details/gt2wjeayxpk.html


<!-- 参考信息 -->