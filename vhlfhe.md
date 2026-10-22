代发 wailian999

[U65] PHP：会话
来源：http://dali.cashguo.top/Article/details/gt2ahgoalus.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2hpwejkrc.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gt2eemamfpl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gt2gffybxut.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gt2gvkignla.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qniwvjxu.html

[U68] PHP：PDO 连接
来源：http://dali.yangfankeji.com/Article/details/gt2tilmifss.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gt2ishgtlam.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gt2xvyjqjxh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.iojbl.cn/Article/details/gt2yvvrykfi.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gt2umqlihsu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gt2uyxpgngn.html

[U71] PHP：抛出异常
来源：http://dali.daria6918.cn/Article/details/gt2sebukdws.html

throw new RuntimeException("失败", 500);
来源：http://dali.cucudq.cn/Article/details/gt2lradjsey.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gt2vttubwwj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yonumen.top/Article/details/gt2yllbmska.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gt2tcipytuc.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gt2zpkurnjk.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2geneyccf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gt2uhqyqxqe.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gt2kordotlb.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gt2elqxnhap.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gt2onqyrfdo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sweek.top/Article/details/gt2scweorzu.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gt2chwgtkjy.html

composer require twig/twig
来源：http://dali.snrcjt.cn/Article/details/gt2drvmtisl.html

[U78] PHP：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvxbsknr.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258888.top/Article/details/gt2zsnqpvzp.html

[U79] PHP：静态分析
来源：http://dali.aizwys.cn/Article/details/gt2mjsnvjws.html

composer require --dev phpstan/phpstan
来源：http://dali.zhongyouzk.top/Article/details/gt2rwllenvt.html

[U80] PHP：代码规范修复
来源：http://dali.snrcjt.cn/Article/details/gt2tjqnsqlj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pycfn.com/Article/details/gt2mjnvyjdl.html

[U81] JS：初始化项目
来源：http://dali.xylfe.cn/Article/details/gt2mwkcsved.html

npm init -y;  npm i express
来源：http://dali.meibo888.top/Article/details/gt2vjpjebrg.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gt2lpgfcjhi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xinyue.icu/Article/details/gt2ozdwvaup.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gt2cqsqrogv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gt2gjqobltk.html

[U84] JS：CommonJS 写法
来源：http://dali.xziqi.cn/Article/details/gt2jedtcjlb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gt2jocdjlfy.html

[U85] JS：可选链
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njuemwic.html

a?.b?.c
来源：http://dali.daria6918.cn/Article/details/gt2wezuwmvb.html

[U86] JS：空值合并
来源：http://dali.hammf.cn/Article/details/gt2gtpycprn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdmtryz.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhsmukna.html

const { a = 1, b = 2 } = obj;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndsstnwb.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gt2ehtxnaei.html

{ ...a, ...b }
来源：http://dali.sxryk.cn/Article/details/gt2ivmrlimb.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gt2iiylfplr.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2dujcnrcl.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adnbwdnd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2uipxwhuy.html

[U91] JS：对象键值遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2urpdpmpe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yongpay.top/Article/details/gt2nqpiuouc.html

[U92] JS：深拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2tdlxospd.html

structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuatttsh.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2xauevjcg.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgsekjgz.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gt2cvurotig.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gt2fwcbrgpj.html

[U95] JS：Promise 包装
来源：http://dali.tanke756.top/Article/details/gt2iinrklmd.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gt2sdzmmvqc.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gt2evtlvpfi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2lwjvsair.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gt2rhkukgqe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2culstqlm.html

[U98] JS：fetch 带 JSON
来源：http://dali.shzxlz.cn/Article/details/gt2fnfrotpl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fijpspyr.html

[U99] JS：事件监听
来源：http://dali.daxiang520.top/Article/details/gt2lwhzlvcb.html

el.addEventListener("click", e => {})
来源：http://dali.0kj1m.cn/Article/details/gt2rtzmspws.html

[U100] JS：DOM 查询
来源：http://dali.gogol.net.cn/Article/details/gt2hliwzhow.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gt2nndutxis.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sllootoh.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gt2wsqheern.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gt2ehnsxfsl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gt2hoeeofcc.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gt2zyqsnhby.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.0kj1m.cn/Article/details/gt2jwfrkpyf.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gt2tilhavqe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2cshodzlj.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gt2hnlozrcp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gt2eacgxyyf.html

[U106] JS：日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2xgjlyxwn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gaohongyu789.top/Article/details/gt2kddaithh.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2olqilbwd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.andypj.xyz/Article/details/gt2sgndewmy.html

[U108] JS：随机整数
来源：http://dali.yongpay.top/Article/details/gt2mpwqpsll.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gt2csmuzenc.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gt2jtdcgypt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2jshufrhr.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gt2shywhfqo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gt2wottzogq.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2iubburkm.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2ceffvaku.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gt2fxkutpdx.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2rygfrhvh.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gt2doderwun.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpquwklf.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gt2udmvendf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2vsciggfu.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gt2tsshrlpt.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtnquudf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gt2hhpzhbsg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2xnstrmvy.html

[U117] JS：单元测试
来源：http://dali.sysykeji.top/Article/details/gt2kxxiwttl.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gt2nwkforlb.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gt2wmsgjubd.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xetlxqah.html

[U119] JS：生产构建
来源：http://dali.hnqzz.top/Article/details/gt2qzlxcpvw.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gt2iontelid.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gt2lfrgctzp.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gt2nhqnyusn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2bsfeedoq.html

统计汇总
来源：http://dali.xziqi.cn/Article/details/gt2zawohvdf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2brtvdbdt.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gt2cnrzyplq.html

Python ......... 252
来源：http://dali.vqdsnc.cn/Article/details/gt2xpfwrppi.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkvftylf.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gt2xhvcylqk.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gt2bghnermi.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uashfrri.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gt2fprfqefo.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2eaavrefk.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gt2jorinebe.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gt2siveftta.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gt2ckyjqsbj.html

SQL ............ 90
来源：http://dali.ppjwa.cn/Article/details/gt2ylpvvqku.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxyglnj.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2bwpuopxh.html

Swift .......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwldijkt.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gt2wltlxwed.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gt2fbmcqwyn.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2feuvujex.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2pscbvjmb.html

合计 ........... 2106 条
来源：http://dali.tianlin.xyz/Article/details/gt2jnrrwttt.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gt2wnltcerb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gt2vzwrcpfj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gt2hrjokszk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2tzikvdfa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gt2ghnszhgc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dashuyun.cn/Article/details/gt2dtsioydx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gt2iqmfispk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2mqbmcuqe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gt2gifqqtzl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2ygmfddef.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2wibovvta.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2ixktdcnb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbmvvoum.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2ophmadjb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2ngbwofwc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ehwqpu.com/Article/details/gt2ipdzzvbi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2xxbpiafg.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gt2ipjfupsu.html

R Bash 专题                             80
来源：http://dali.shzxlz.cn/Article/details/gt2zbraemjh.html

S C / C++ 专题                          60
来源：http://dali.yvedp.cn/Article/details/gt2ygxqsbuc.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrxiyhbw.html

U 高频实用片段                         120
来源：http://dali.shzxlz.cn/Article/details/gt2pxuhxzow.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2npxigvck.html

合计                                  2106 条
来源：http://dali.yanxiufei.cn/Article/details/gt2hjdidzsp.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2txzzzwhf.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gt2errxvrkb.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gufpuatu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhoulong.xyz/Article/details/gt2altkcpsd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmsyrfeg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.kuanghao11.cn/Article/details/gt2fxefqapl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gt2arglajfi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gt2uvenkfhu.html

—— 文件结束 ——
来源：http://dali.meibo888.top/Article/details/gt2hsnfwfrd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2riqqweqa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vunhdlje.html

Common Programming Examples Cheat Book
来源：http://dali.xuetiantiany.cn/Article/details/gt2zomsfvlo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2esmxyvdt.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gt2zehvqhbc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gt2lggcalzn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sysykeji.top/Article/details/gt2hydcabhs.html

SQL · Bash · C · C++
来源：http://dali.sxryk.cn/Article/details/gt2roanlvem.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sxryk.cn/Article/details/gt2lnzzxoqx.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gt2xqvstnjo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggdnqtfr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gt2ksrandbs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yvedp.cn/Article/details/gt2fxsswadd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenjidiqi.icu/Article/details/gt2pigzidwa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guowangkeji.top/Article/details/gt2ofvpudrw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gt2itdbogsq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gt2zyayjsng.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pviixyje.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gt2bwcyqxzd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gt2zbmfjsck.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hfpthk.cn/Article/details/gt2enclcflc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gt2ezlgtqcr.html

【文件统计】
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfkdmvok.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gt2fpedrwit.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2frvfqugo.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gt2atqjntsl.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2uhpdzfud.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gt2szrkrqos.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gt2yqpbeggz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2hpinxfoz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gt2dzeghpmh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gotoacloud.top/Article/details/gt2xefvpxgj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gt2nvwchtbs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gt2xveggsap.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhixingplan.top/Article/details/gt2laugpeju.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2ljaafumk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gt2vdhabwtk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2otmfnzln.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2xenixgfu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2hcafjitn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gt2sgwyzwik.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ldpdeiqr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2nsnmsaiv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gt2fvgqancq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxinkj.top/Article/details/gt2xjjlesto.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2ddtgqauw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2hyknzjie.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gt2tlgufeht.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ziyhglfw.html

A. 基础语法与类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2thrylpne.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jdwmeate.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2nczsbzyc.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gt2bkpqxjpm.html

PHP:  echo "Hello, World!";
来源：http://dali.iojbl.cn/Article/details/gt2nmiiroad.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gt2ktmomeyd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gt2yhvjaqcd.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gt2rwdnawox.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gt2wvlepbls.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gt2jojtldnv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2ephuuxcr.html

[A02] 变量声明与赋值
来源：http://dali.tanke756.top/Article/details/gt2wuxgfine.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2eoqlhsvw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2ggutleap.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gt2klvzqeww.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2ivzkjueg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgayezmv.html

Go:   name := "Alex"; age := 20
来源：http://dali.xziqi.cn/Article/details/gt2fuahpvtr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdhzgoex.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gt2nujjzalm.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gt2bkiutboo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zycfv.cn/Article/details/gt2mgkinqvm.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmqbvukq.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrcyhpce.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2wmofsoau.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhysomfh.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvhuddmp.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2iyxywuqb.html

C#:   const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2cwxdpjwh.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2vcpsndim.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gt2yqwdtlru.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gt2vvnzfkal.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2stzxpxkh.html

TS:   typeof x; x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gt2dgqbwmda.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gaohongyu789.top/Article/details/gt2osovqbtf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gt2wdczneam.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gt2gzoxqwvj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gt2iqomqpzw.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gt2ueuliaqi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gt2cvuwrksd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2vbwsldfj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2uaedndbm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2jrcrxiso.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzgqryif.html

Go:   7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2fqselzvq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2ulvjapbi.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2kxerzsoe.html

[A06] 字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2aviklsha.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyjaltpd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojxfmoks.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gt2jwunbgwt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2iijvfpun.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gt2dtuanylj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxsrbds.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gt2nojqcwoi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tianlin.xyz/Article/details/gt2rdwsvixw.html

[A07] 数字转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2whmbjdym.html

Py:   str(42)
来源：http://dali.zycfv.cn/Article/details/gt2sswzhjie.html

PHP:  (string) 42; strval(42)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqfkrsou.html

JS:   String(42); (42).toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhiehxrl.html

TS:   String(42)
来源：http://dali.daria6918.cn/Article/details/gt2zyiambld.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aizwys.cn/Article/details/gt2xpsskqvw.html

Go:   strconv.Itoa(42)
来源：http://dali.hnqzz.top/Article/details/gt2prxlgcuv.html

Ruby: 42.to_s
来源：http://dali.ehwqpu.com/Article/details/gt2vjcwvazj.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gt2rraqqzcr.html

[A08] 取整与四舍五入
来源：http://dali.yanxiufei.cn/Article/details/gt2qlexuncf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2jqpmserg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmxignmy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gt2aaixtfka.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hfpthk.cn/Article/details/gt2fjtgfdnj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2tjetctes.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gt2pzgxwotu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gt2aqkxxbfd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gt2wywndqyh.html

[A09] 绝对值与最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcahnmku.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2wpyetvbp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2gdgenbpi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpapwhxg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2chgpygxw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvhxojtu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.haohaochexian.top/Article/details/gt2uwedoyqs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zycfv.cn/Article/details/gt2sxtklato.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2llmjaamr.html


<!-- 参考信息 -->