代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtdgchdihy.html

$v = $a ?? $b ?? "default";
来源：http://dali.guannengcc.top/Article/details/gtdwhdhcym.html

[U54] PHP：空安全调用
来源：http://dali.kuanghao11.cn/Article/details/gtbjvwbqtc.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gtoypzgzvf.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtxbelaqbl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gthqhhqltm.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gtktymthwr.html

f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbqidpasm.html

[U57] PHP：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtxoramrty.html

"值: {$a}"
来源：http://dali.gogol.net.cn/Article/details/gtsznikhpc.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gttjnizddz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtjfqgjiru.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gtfaozasvn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtjspinwra.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwhqighw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdxswmqi.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gttpelutum.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveqcznlv.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gtvfxlmzay.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gtojegbaai.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gtchtpjbtw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hysaishi.cn/Article/details/gtkzifvyuk.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gtiyzcnbif.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ehwqpu.com/Article/details/gtvizfuxxq.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gtbmhqqnvp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtebwpiaum.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqasakwzt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgufenzy.top/Article/details/gtsybxprcp.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258888.top/Article/details/gtuooviktn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gtsnmjiqjj.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gtbbbegcvo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfiemwwy.html

[U69] PHP：PDO 预处理
来源：http://dali.sufxvd.cn/Article/details/gtvfpsieub.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guannengcc.top/Article/details/gtvxwyulwh.html

[U70] PHP：PDO 事务
来源：http://dali.ivvv.top/Article/details/gtuwmiwcbk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sweek.top/Article/details/gtgghjamgc.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtkgfoozeu.html

throw new RuntimeException("失败", 500);
来源：http://dali.pycfn.com/Article/details/gtgpeoxrqb.html

[U72] PHP：写错误日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgcynsgn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gtxmoqgyum.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtmedqvlyn.html

parse_ini_file("config.ini", true)
来源：http://dali.yangfankeji.com/Article/details/gtxjbkikte.html

[U74] PHP：读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtxwuzhodf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gtytbuylpa.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtneeoiptw.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gtikuossgs.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtboyjioqd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gtplerzjoh.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gtvafvqsot.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gtkfdubocd.html

[U78] PHP：单元测试
来源：http://dali.redwolf501.top/Article/details/gtjycnxtha.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtndutrlyh.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gtxmtinltt.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gtgpprwtyg.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gttiqbeulc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gtzzyrhyfc.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gtiahiubrd.html

npm init -y;  npm i express
来源：http://dali.ehwqpu.com/Article/details/gtjhxqqdon.html

[U82] JS：package.json 脚本
来源：http://dali.jqgufenzy.top/Article/details/gtbjyqmpbm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258888.top/Article/details/gturdbjomt.html

[U83] JS：ES Module 导入导出
来源：http://dali.xylfe.cn/Article/details/gtobuyylbj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtafajhrgh.html

[U84] JS：CommonJS 写法
来源：http://dali.wangdashe.top/Article/details/gtfgoszvoy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258888.top/Article/details/gtxojhcguc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gteyooxprs.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiosdbqh.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gthfvtwnie.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gtwghexomp.html

[U87] JS：解构默认值
来源：http://dali.smart0.xyz/Article/details/gtuypalxfl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gtyphypbjg.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gtfgxkvucc.html

{ ...a, ...b }
来源：http://dali.havefunace.top/Article/details/gtmxytpfdu.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtgrbmujtw.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtjrlmsdra.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gtlinphmsq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtiwazkwoj.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gticuqsksd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gtezrcegje.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gtkexxlshb.html

structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjopipwgb.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gtaxfzuhrx.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gtgxdvxkkr.html

[U94] JS：箭头函数
来源：http://dali.316326.xyz/Article/details/gtohexjmnm.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtwejglemm.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtueolmfyk.html

new Promise((resolve, reject) => {})
来源：http://dali.aibaodan.cn/Article/details/gtydrmvvyj.html

[U96] JS：async/await 与异常
来源：http://dali.hywenlv.cn/Article/details/gtdktsfoku.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtfxyiklww.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gtjfcbelal.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtzbftimcc.html

[U98] JS：fetch 带 JSON
来源：http://dali.cashguo.top/Article/details/gtqpwfwrkf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gtwfbeqsrs.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gtexmfzicz.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtkzdqrsgg.html

[U100] JS：DOM 查询
来源：http://dali.ivvv.top/Article/details/gtvaxgysgy.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtzhknicoc.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokvzpqef.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdybtaxo.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrsrhiee.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtvuwwkpwo.html

[U103] JS：定时器
来源：http://dali.iojbl.cn/Article/details/gtzjnmtvxq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtiutmrczg.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtjxxitpbz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtdvltpwyg.html

[U105] JS：节流
来源：http://dali.zhongyouzk.top/Article/details/gtcwducbkc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtttnepbuy.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtciqkpyby.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtipmxthlw.html

[U107] JS：数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtcnadudrk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gthpmmwqjx.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gtcyttugri.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gttkdernpb.html

[U109] JS：数组分组
来源：http://dali.haohaochexian.top/Article/details/gtbfkgiuah.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gthaftbexf.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gthkrbmhjj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gtiuuizxyb.html

[U111] JS：对象转 Map
来源：http://dali.birdmap.top/Article/details/gtraaxfmte.html

new Map(Object.entries(obj))
来源：http://dali.bjfxy.top/Article/details/gtuizfvkhs.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gtksnoamot.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtlgatkiim.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtpcxskxfo.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtcfhrjrzy.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gtevqzloae.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtvoozlbss.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtcsicrnic.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtquxisfvb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gthnrokgbu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuxming.cn/Article/details/gtasuhvkwv.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtjhjjvvai.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtancstomx.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gtlsgftlbf.html

npm i -D vite;  npx vite
来源：http://dali.yonumen.top/Article/details/gtymhrngzw.html

[U119] JS：生产构建
来源：http://dali.fzhhl.top/Article/details/gtwprafatr.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gtppwajudl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.316326.xyz/Article/details/gtipzqdzly.html

import.meta.env.VITE_API_URL
来源：http://dali.zhongyouzk.top/Article/details/gtidnloimy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkenzlett.html

统计汇总
来源：http://dali.feifeiyinyue.top/Article/details/gtrfimvhlf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtylcbcgnb.html

按语言统计（条）：
来源：http://dali.chenlongwang.top/Article/details/gtnlrmqgqg.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtzepuconk.html

PHP ............ 252
来源：http://dali.hammf.cn/Article/details/gtphaobejm.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtfxcroaeu.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gthlqatqtg.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtuatchbeo.html

Go ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtgbzjvpvm.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gtkbvbybnc.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtxktrqtdw.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtylpijrkw.html

C++ ............ 30
来源：http://dali.nanxinkj.top/Article/details/gtdlbiltkm.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtihwqurdo.html

Bash ........... 80
来源：http://dali.xuanzx.com/Article/details/gtdqqqvcir.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbgextve.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gtwofptbcl.html

Lua ............ 10
来源：http://dali.havefunace.top/Article/details/gtckjgevja.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gtmtfmcyrd.html

Scala .......... 10
来源：http://dali.jlsjyb.cn/Article/details/gtlmkvfjkp.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtdidqwwav.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gtvpohihek.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gtcjgkfdgc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtgxuxajbu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtiugjgpoh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtgrypfvjj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtzelquqiy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gtvtryzrww.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtyliokxsg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtmnnbzrqv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtdnbdfcje.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtkcadognw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtpubdcwhw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtozyphuwx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtgtdhsxxr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtzsbidkpn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtuplsnfyg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgufenzy.top/Article/details/gtlctoulcx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtcufzahoj.html

Q SQL 专题                              90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbibqvryq.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gtaitkfxiv.html

S C / C++ 专题                          60
来源：http://dali.gogol.net.cn/Article/details/gtbmwmfmzo.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtudbxjilw.html

U 高频实用片段                         120
来源：http://dali.aibaodan.cn/Article/details/gtiowimzui.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtwemjuicc.html

合计                                  2106 条
来源：http://dali.xylfe.cn/Article/details/gtviynxufz.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkkiqeds.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gtjfwdxsoy.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gteaigidar.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtactmhbse.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.quarkkingdee.top/Article/details/gtpvjsysnp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.snrcjt.cn/Article/details/gtxywczkop.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gtktrxacis.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gthellrkcl.html

—— 文件结束 ——
来源：http://dali.0kj1m.cn/Article/details/gtfuiolfvd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpzshatcw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxmfkheh.html

Common Programming Examples Cheat Book
来源：http://dali.sxryk.cn/Article/details/gtfydvqyjz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtruakrfcd.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gtrgvwfyny.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gtbijulnyi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gtvfkawpjv.html

SQL · Bash · C · C++
来源：http://dali.shangyingyoupin.top/Article/details/gtjlbmdvdv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuetiantiany.cn/Article/details/gtflhkgyet.html

【使用说明】
来源：http://dali.ydzc1.top/Article/details/gtfrezkkfo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dianchejie.cn/Article/details/gtyerbocww.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.316326.xyz/Article/details/gtdnwhyxgt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.meibo888.top/Article/details/gtrpvvmubz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.havefunace.top/Article/details/gtuqykrcks.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ppjwa.cn/Article/details/gtrxgjdect.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gthjkhvtfj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.c1oappe.top/Article/details/gtqlpcxoaq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj202588.top/Article/details/gtnfhdybqn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gtgnxfwvpo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xziqi.cn/Article/details/gtsbcghjrw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gtsgeqtwbr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj202588.top/Article/details/gtiackjpbv.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gtnwtkiayj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypjiiyil.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtpsfzlooo.html

目  录
来源：http://dali.jqgufenzy.top/Article/details/gtztvnwebq.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtrnujrmae.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtwkdpwjrh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtdhrgcmke.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtngfslfrg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gtagrljewa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ehwqpu.com/Article/details/gtinrdbgdt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gthbzueoeh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtqigzthgu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtzxvbyczu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtnzfdexpc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtwcudhlem.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtlehzmklp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtfvgniznz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtwummdomn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtuxahaotd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gtheskxplw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtumtvugas.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlhpcoyc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtiqdgrcie.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nwbrower.top/Article/details/gtdaazynrr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtwdbsalch.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtzchjueyy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthyrdldkp.html

A. 基础语法与类型
来源：http://dali.0kj1m.cn/Article/details/gtbijcyeql.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtikkhpcxl.html

[A01] Hello World
来源：http://dali.hysaishi.cn/Article/details/gtefmocqco.html

Py:   print("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gtyhqwmwsy.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gtebzjiuhs.html

JS:   console.log("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtwejfoony.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yangfankeji.com/Article/details/gtqwjlwfqj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtysltfpuv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtplucjvhq.html

Ruby: puts "Hello, World!"
来源：http://dali.ehwqpu.com/Article/details/gtsslejmix.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gttnbwdzyv.html

[A02] 变量声明与赋值
来源：http://dali.wangdashe.top/Article/details/gtydgxrwhg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gtikoykfbk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gtoqxewljc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gttswzndtj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dashuyun.cn/Article/details/gtzipfymgj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtxdfkwzmh.html

Go:   name := "Alex"; age := 20
来源：http://dali.gzhubu.top/Article/details/gtmafgvscq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sxryk.cn/Article/details/gteusmzhhg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtcwopdaek.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gtdrfxljiq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hfpthk.cn/Article/details/gtwomvkrql.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtyrbppwks.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnxuoddr.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtzkiqjqmx.html

Java: static final double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtcvyzjvoo.html

Go:   const PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolsjmepa.html

Ruby: PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtoinnxscu.html

C#:   const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtfoypgxyq.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gthkfsvrkk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pycfn.com/Article/details/gtrqulrxja.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fengsongda.top/Article/details/gtecbjztog.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtwxhwfmmn.html

TS:   typeof x; x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtmqqepfkd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhongyouzk.top/Article/details/gtwzzwwdnv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sxryk.cn/Article/details/gtttspblzo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigufen.top/Article/details/gtbehujury.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gtwyyxqncs.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gtsdwjhwab.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sufxvd.cn/Article/details/gtubykdkrm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtjmtlocpp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtfafnqsld.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtnyjecgsn.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtipydwtji.html

Go:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtholwepzv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtavjdpwbm.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtihrorndj.html

[A06] 字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtkdulkzgh.html

Py:   int("42"); float("3.14")
来源：http://dali.meibo888.top/Article/details/gtkwxqnfem.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtwvmamnqt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtxaepmpzc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yonumen.top/Article/details/gtfajanhho.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yongpay.top/Article/details/gtqxmvqhwk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gtpqihszgx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gtmwhaeftg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daxiang520.top/Article/details/gtzuqfacbj.html

[A07] 数字转字符串
来源：http://dali.xylfe.cn/Article/details/gtfndbchad.html

Py:   str(42)
来源：http://dali.cheryme.top/Article/details/gtfxgniwdi.html

PHP:  (string) 42; strval(42)
来源：http://dali.cqqwz.cn/Article/details/gtxbusboxz.html


<!-- 参考信息 -->