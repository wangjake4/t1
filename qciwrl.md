代发 wailian999

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gtzipxonvq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtqjvhgidx.html

[U62] PHP：日期对象
来源：http://dali.cheryme.top/Article/details/gtpzskvzfp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtjsqugxcv.html

[U63] PHP：文件读写
来源：http://dali.quarkkingdee.top/Article/details/gtttkkaisz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gtmorpzzrr.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtwtfgbzhw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnqzz.top/Article/details/gtyomomwtm.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gtkrftwfwt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtvvjlouvu.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtdxoumikd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yueranfly.top/Article/details/gtnjxcfqjo.html

[U67] PHP：处理文件上传
来源：http://dali.zhiwuduotai.top/Article/details/gthfsipfan.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gthsgzzgma.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gtsoujlrka.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gtwpvseqit.html

[U69] PHP：PDO 预处理
来源：http://dali.cheryme.top/Article/details/gtaqggkpyf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigufen.top/Article/details/gtsgaaswfr.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gtfsatrhyt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gtnmlgekqi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtctzemxpg.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtbowshrwh.html

[U72] PHP：写错误日志
来源：http://dali.chenjidiqi.icu/Article/details/gtysvvejol.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yongpay.top/Article/details/gtlyimkslf.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gtvvrjxriy.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gtayhnwrlk.html

[U74] PHP：读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtwistsddw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gthspaylav.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gtsyvliedq.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gthhhkltbp.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gttsnxuoih.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gtiarealuk.html

[U77] PHP：模板渲染
来源：http://dali.mhx1999.top/Article/details/gtktbwjajy.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgbhbtik.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gtfsockkwv.html

composer require --dev phpunit/phpunit
来源：http://dali.zycfv.cn/Article/details/gtczrxuqjp.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gtvqwmttaw.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gtewbjqoaq.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gtpdybvmyz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtcnpwbcoq.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gtmmljxgdm.html

npm init -y;  npm i express
来源：http://dali.316326.xyz/Article/details/gtidxuyuod.html

[U82] JS：package.json 脚本
来源：http://dali.aibaodan.cn/Article/details/gtklguunrn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigufen.top/Article/details/gtralifhrd.html

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfiludwz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtgcmpgtzc.html

[U84] JS：CommonJS 写法
来源：http://dali.gaohongyu789.top/Article/details/gtqxcxviyf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtdepecncl.html

[U85] JS：可选链
来源：http://dali.aibaodan.cn/Article/details/gtxixzbgkl.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gtgfmssjmj.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gtczchylfi.html

a ?? b
来源：http://dali.jlsjyb.cn/Article/details/gtwtzsvlnt.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtsqbzjvyw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sweek.top/Article/details/gtdidrlbqi.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gterpjwwkg.html

{ ...a, ...b }
来源：http://dali.sxryk.cn/Article/details/gtqowtpdpp.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gtcehqsvig.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauaplwey.html

[U90] JS：数字数组排序
来源：http://dali.ivvv.top/Article/details/gtwzflripj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtiwmeksds.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtwxnibcht.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmchavzbe.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtysrvhnlv.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtdzyjdoss.html

[U93] JS：模板字符串
来源：http://dali.cqqwz.cn/Article/details/gtqsumicip.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gtvsbgywwb.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtggbioxow.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtwoaflkle.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gtjssteble.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gtkzzxqzet.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gtmnqeprsv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjmxbibf.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gtxsqdunoa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtdvdnwpzw.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtuybwqlhh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gtgtdgpmdm.html

[U99] JS：事件监听
来源：http://dali.chenlongwang.top/Article/details/gtlnxtkfjs.html

el.addEventListener("click", e => {})
来源：http://dali.hnqzz.top/Article/details/gtpkwfmdwq.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gtysgysizx.html

document.querySelector(".item")
来源：http://dali.jqgufenzy.top/Article/details/gtsstgfgad.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gteddicwby.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlikjumq.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gtrsvtzhlg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gtdcsfkuru.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gtsqxivlct.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gtjmfimbbc.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtbxqwdqpz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtyhlnhihg.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gtxppjguzh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gtcoigzrhx.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gtdgmghtyi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.smart0.xyz/Article/details/gtzhyeysum.html

[U107] JS：数字千分位
来源：http://dali.yj202588.top/Article/details/gtlcacehvm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtmnlwhssj.html

[U108] JS：随机整数
来源：http://dali.fzhhl.top/Article/details/gtfihszlyf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gtpsoxozmm.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtmwhwyrhz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtppccnptt.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gtduiuxrxy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gtdhhyfxvk.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtyzxahuoh.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gtppmhztfs.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gthtzgqrmj.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtksanrbmd.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gtsytytwnc.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtrincaszi.html

[U114] JS：JSON 深比较
来源：http://dali.yangfankeji.com/Article/details/gtvmfdccab.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtncadaofw.html

[U115] JS：生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtkbtowuqf.html

crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtcwwhdeee.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtlatptegz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenlongwang.top/Article/details/gtppynbzag.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtbucokzkr.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtkbingrlz.html

[U118] JS：开发服务器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjecrwgnd.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtahtufluv.html

[U119] JS：生产构建
来源：http://dali.fzhhl.top/Article/details/gtjqngqtrr.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gttvmzyftk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtciazmvhg.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtykeonnol.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbrjksxxt.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gttevlthmk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdapmwfuc.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtrutpswuf.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gtapqbalgy.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gtzbrlbmth.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtsdilckvt.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtmeczspot.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gtphcirxkr.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtfusbcdtc.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtismqziby.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtekxyoamp.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtjbnezeqf.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gtdddxrdog.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtelhszlht.html

Bash ........... 80
来源：http://dali.hysaishi.cn/Article/details/gtmggknsif.html

Kotlin ......... 15
来源：http://dali.zhoulong.xyz/Article/details/gtamtlfzue.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtsobxakvz.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gtgqsmvlxo.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtqenhtopt.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gtfsztcowq.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtkayutzzf.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gtqqrvwpyq.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gtglewoknz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtqvnosyku.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtpulniheh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gteejhrqcs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtlpehxiqe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jiagoushi.top/Article/details/gtetwtllzz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtwrzxpejq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtcmsofzen.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gttegeqtdb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtmbquhqvt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtkxkcjroj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gttjjolpdn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtqfueanrt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtcwssypnm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtzugsfonq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtrcpfywua.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtriuqyjfv.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gtrejnhhwg.html

R Bash 专题                             80
来源：http://dali.jyoumei.cn/Article/details/gtagrvpoey.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gtfdvidtym.html

T 其他语言补充                          60
来源：http://dali.aizwys.cn/Article/details/gtoiazzaun.html

U 高频实用片段                         120
来源：http://dali.dashuyun.cn/Article/details/gttghkwytj.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtktrnmsar.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gtsywmkvvm.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtjwvijtzj.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtvmoyxxnl.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtrpdkjfdc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenjidiqi.icu/Article/details/gtpyayljjg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aizwys.cn/Article/details/gtakdevkju.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhixingplan.top/Article/details/gttwibgawk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gtnbzhaynv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aibaodan.cn/Article/details/gtptnaqjfa.html

—— 文件结束 ——
来源：http://dali.zhongyouzk.top/Article/details/gtantpghte.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtotryytqr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gtbgyeocow.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtagfsxfmz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsyzcitcp.html

【收录内容】
来源：http://dali.sweek.top/Article/details/gtybakguea.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtxnclkvbv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gtlagxgthv.html

SQL · Bash · C · C++
来源：http://dali.nanxinkj.top/Article/details/gtcisesxcy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gtkbjvskji.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gtwpdqzqtx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazatafhb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gtllakxchz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daria6918.cn/Article/details/gtcefqweqk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.smart0.xyz/Article/details/gtynvnnfrm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sufxvd.cn/Article/details/gtrhwkqiki.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gttliwllva.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gtyoyfaynd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yanxiufei.cn/Article/details/gtzwcchwzi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gtcnrdbfij.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yongpay.top/Article/details/gtjzgfnrun.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yongpay.top/Article/details/gtkfawyszo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaninjabs.html

【文件统计】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgetgcep.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtvikkaftu.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtkysztcrs.html

目  录
来源：http://dali.kuanghao11.cn/Article/details/gttvurnzrs.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtwilqomqc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtykjfegwj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gttqrogxvm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtgskbksyi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtpgcexece.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dashuyun.cn/Article/details/gtfheanjng.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtjbahfhsm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtxvkrkkxl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtsrbfmvef.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtbybxzsqx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtyxdxtsqp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtplgckxyn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gthosifawe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtmqkatulm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gtyxjgytxm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiciwxpu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtvmhgmrch.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj202588.top/Article/details/gtdqqacypd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtayqzheph.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.redwolf501.top/Article/details/gtfwjcfhmy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtbzdlykqb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtzqzzbhnk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgzoldjfu.html

A. 基础语法与类型
来源：http://dali.pengpengdd.cyou/Article/details/gtkzrggadf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjqlagesx.html

[A01] Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtdayalkeg.html

Py:   print("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gttybkrzhw.html

PHP:  echo "Hello, World!";
来源：http://dali.yvedp.cn/Article/details/gtehbkwzdx.html

JS:   console.log("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtxpxhcwsh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuanzhike.top/Article/details/gtsbibstkk.html

Java: System.out.println("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtplebxfzn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gtfstulwlw.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gtlnruvhbz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtwmrxians.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gtotmuvydj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aibaodan.cn/Article/details/gtflspbdig.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtbjxmrmqz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtynhkqxdp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zdqjudy.top/Article/details/gtjvfxkotd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtiqfsogzy.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwidxjqn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shuidangran.top/Article/details/gtgzlodgbj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gteebedkou.html

[A03] 常量定义
来源：http://dali.yuxming.cn/Article/details/gtnvzfwjyk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ehwqpu.com/Article/details/gtxpusntyn.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtkyfuvqmh.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtjdelbaeo.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtzlqhtalj.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtqqotspgo.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtzxkejptl.html

Ruby: PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gttakswxxm.html

C#:   const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gttbjbrqzk.html

[A04] 判断变量类型
来源：http://dali.yuanzhike.top/Article/details/gtptkbjbzs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuetiantiany.cn/Article/details/gtsonhnyki.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gtqftxugut.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtzcqbkgdq.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtcboxwkxf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guannengcc.top/Article/details/gtqqutupdh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigufen.top/Article/details/gtpovnqsvk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhengqikj.top/Article/details/gtjeamkgpx.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtvzuenbql.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gtkugupfvr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gtuxrvfbqt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtgewdvpld.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtcnkukoid.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtmavnysyv.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtirozfiau.html

Go:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtmvscugbq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtusqmxnxg.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtishhufnn.html

[A06] 字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtkvprhuww.html

Py:   int("42"); float("3.14")
来源：http://dali.sweek.top/Article/details/gtenufcfhz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ydzc1.top/Article/details/gtjxwlfodz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbexwteh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gthqdxswjz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfarhtwxn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zycfv.cn/Article/details/gtuxouveig.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqnrudnk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hnqzz.top/Article/details/gtazpqoutw.html

[A07] 数字转字符串
来源：http://dali.hnqzz.top/Article/details/gtgquaihzv.html

Py:   str(42)
来源：http://dali.cdnleiting.top/Article/details/gtxqbpziti.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtapqtlcfk.html

JS:   String(42); (42).toString()
来源：http://dali.cheryme.top/Article/details/gtcthqyvqe.html

TS:   String(42)
来源：http://dali.sweek.top/Article/details/gtjpbuhxie.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbeytggp.html

Go:   strconv.Itoa(42)
来源：http://dali.cdnleiting.top/Article/details/gtyvkskdla.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gtoyvhouuh.html

C#:   42.ToString()
来源：http://dali.iojbl.cn/Article/details/gtlfpodwlw.html

[A08] 取整与四舍五入
来源：http://dali.jlsjyb.cn/Article/details/gtpahlkpsx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gtpvwnddgt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hysaishi.cn/Article/details/gtieztrwst.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtbgwbvzts.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtpdempwiv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvcumhjp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtucxrzqjo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yonumen.top/Article/details/gtggqhwlwl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtbkghhjoa.html

[A09] 绝对值与最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtheszcult.html


<!-- 参考信息 -->