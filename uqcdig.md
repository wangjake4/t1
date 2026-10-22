代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.0kj1m.cn/Article/details/gt2inakeumj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gt2uoodewsn.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2efooeexf.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2yrbiltky.html

[U57] PHP：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2sbdxwjab.html

"值: {$a}"
来源：http://dali.ppjwa.cn/Article/details/gt2nnmxxoaf.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gt2opfouygw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2odovgtca.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gt2sgeyhulr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2vqgesljt.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gt2vyuxkduk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gt2ppsprbjj.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gt2ojqvqbpp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2uclbfzco.html

[U62] PHP：日期对象
来源：http://dali.snrcjt.cn/Article/details/gt2fjixgmqt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gt2ugvjzazj.html

[U63] PHP：文件读写
来源：http://dali.quarkkingdee.top/Article/details/gt2hgpvdggt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gt2gdkhenxx.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gt2wwekkzac.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gt2qszlpepe.html

[U65] PHP：会话
来源：http://dali.9152youxi.cn/Article/details/gt2uemknuuu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fszrewza.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzjtqnvb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gt2dekskegb.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gt2qtyqwtnn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gt2thwptjgt.html

[U68] PHP：PDO 连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwgjznqh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gt2xzisrosi.html

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gt2mmjmowqx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gt2hwvvxblc.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gt2alvcxmkd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cashguo.top/Article/details/gt2bkinpppl.html

[U71] PHP：抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2illgcevd.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gt2vtrszwis.html

[U72] PHP：写错误日志
来源：http://dali.yonumen.top/Article/details/gt2gpyahbnb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yriqtouh.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gt2dpbnrcwu.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gt2jkqaiozs.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnetvmxp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gt2bjjsfncj.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gt2xwoeesso.html

composer require psr/container
来源：http://dali.yj20258.top/Article/details/gt2fvfrbgvt.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukfgajey.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgfzy.top/Article/details/gt2kdburdca.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gt2fuysyzdv.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gt2geircapz.html

[U78] PHP：单元测试
来源：http://dali.cheryme.top/Article/details/gt2mhvfgsmu.html

composer require --dev phpunit/phpunit
来源：http://dali.chenlongwang.top/Article/details/gt2pjvlmbon.html

[U79] PHP：静态分析
来源：http://dali.birdmap.top/Article/details/gt2ndxywfpk.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gt2wtgsczqi.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmfnnfgr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuetiantiany.cn/Article/details/gt2cumyqslf.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gt2slgpznyg.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gt2knzntasm.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gt2zwajihiz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gt2airuvtbo.html

[U83] JS：ES Module 导入导出
来源：http://dali.316326.xyz/Article/details/gt2ooyssyqv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gt2ukbppetd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhixingplan.top/Article/details/gt2igtfgxkw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenzaomai.com/Article/details/gt2azsamamt.html

[U85] JS：可选链
来源：http://dali.sweek.top/Article/details/gt2bjudyzli.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gt2oszetebg.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gt2icspxsau.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gt2mzsqcmoa.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tphitdac.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gt2jpeokgfu.html

[U88] JS：对象展开合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2mabpdoyd.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gt2knwhertn.html

[U89] JS：数组去重
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqfwpztv.html

[...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2guwbkbbc.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmbbvgwt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2vszzyfjh.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gt2ldointxr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shzxlz.cn/Article/details/gt2iijopmbt.html

[U92] JS：深拷贝
来源：http://dali.fengsongda.top/Article/details/gt2hlndlpms.html

structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2iwejbtvh.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2mirqpagk.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gt2yxjnwdea.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gt2rkpymckh.html

const double = x => x * 2;
来源：http://dali.jinqigufen.top/Article/details/gt2fitjzbky.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gt2bfvqhyhf.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gt2umncemnl.html

[U96] JS：async/await 与异常
来源：http://dali.daxiang520.top/Article/details/gt2aepdmjec.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2gjnqnlri.html

[U97] JS：并发请求
来源：http://dali.cheryme.top/Article/details/gt2iyhzdyul.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2gxflvjho.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrbqbuah.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gt2xnaxugxn.html

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gt2qxhmximg.html

el.addEventListener("click", e => {})
来源：http://dali.meibo888.top/Article/details/gt2xcfthqjs.html

[U100] JS：DOM 查询
来源：http://dali.tianlin.xyz/Article/details/gt2zisihkpr.html

document.querySelector(".item")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvdjsqiv.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpkrvcms.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gt2jktevznc.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gt2dpmsyqlf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gt2uuptpjpr.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gt2hzufktzy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gt2qblkgzvo.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gt2fkztsoag.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2tqzemhpq.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gt2etntduxl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gt2ytlacwwy.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2puupfdlh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gt2vqtofodl.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gt2clkuybor.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gt2iibqodrx.html

[U108] JS：随机整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwdilusl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258.top/Article/details/gt2lxlsrbya.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gt2jvwzhorh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2unozzuwj.html

[U110] JS：数组分块
来源：http://dali.fzhhl.top/Article/details/gt2bleelxia.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gt2oxwhsoco.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gt2dvykdqjp.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2mvwduwzt.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gt2ooffonhm.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2bsuhqsvv.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaymwbgh.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2ksnqgkro.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2mugrmtyz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gt2ehiwddpd.html

[U115] JS：生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2gbtadsaf.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2najwttqv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jlsjyb.cn/Article/details/gt2vmzpchub.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gt2oivhqddq.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gt2ilqtorxs.html

npm i -D vitest;  npx vitest
来源：http://dali.316326.xyz/Article/details/gt2rxrphpoc.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2wotohkfj.html

npm i -D vite;  npx vite
来源：http://dali.9152youxi.cn/Article/details/gt2sdnmgwfl.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gt2dxluvxgl.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gt2xlkowozj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gt2yysyohog.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gt2kauqashc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2foddsnxa.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gt2bcspmrqw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dicyvyat.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gt2iimoivgm.html

Python ......... 252
来源：http://dali.tanke756.top/Article/details/gt2hgvmztew.html

PHP ............ 252
来源：http://dali.daxiang520.top/Article/details/gt2qamunuio.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gt2hmbuubov.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2eaokpfok.html

Java ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2uleavmzm.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2zzubwltw.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2foxwzdbm.html

C# ............. 212
来源：http://dali.nanxinkj.top/Article/details/gt2aqwhscqh.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plwqskzb.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lenrljsu.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gt2ootnoyxo.html

Bash ........... 80
来源：http://dali.c1oappe.top/Article/details/gt2ozmalqek.html

Kotlin ......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxftzotc.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gt2ibgzeuxj.html

Lua ............ 10
来源：http://dali.redwolf501.top/Article/details/gt2jrwshzlo.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gt2rtbaxlez.html

Scala .......... 10
来源：http://dali.jqgufenzy.top/Article/details/gt2eomepzuv.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2aggcnpvn.html

合计 ........... 2106 条
来源：http://dali.cdnleiting.top/Article/details/gt2facluitg.html

按章节统计：
来源：http://dali.jlsjyb.cn/Article/details/gt2grqanzyc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gt2bmeahqpw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gt2kyfjhvid.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gt2avmbymhk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gt2mleylcjp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.meibo888.top/Article/details/gt2daexwtaj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gt2urioeqcj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gt2mtwhwsga.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gt2shzaqesj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2ptacrsze.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gt2suchxyoo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2oszbqnzk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2kthoahju.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2mcjpphkw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prgmdsox.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2leldxsay.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwkyahde.html

Q SQL 专题                              90
来源：http://dali.yuxming.cn/Article/details/gt2wyzxjjvx.html

R Bash 专题                             80
来源：http://dali.jqgfzy.top/Article/details/gt2zpyrbozo.html

S C / C++ 专题                          60
来源：http://dali.zycfv.cn/Article/details/gt2rnkxdgmi.html

T 其他语言补充                          60
来源：http://dali.birdmap.top/Article/details/gt2bijcsdos.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gt2sspsvqiz.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2dzjbjumi.html

合计                                  2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2xjohyuzu.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gt2avczoygu.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gt2cvwiqtbc.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2gqavlmxg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258888.top/Article/details/gt2qqhnzktj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sufxvd.cn/Article/details/gt2nimgpoii.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gt2ctzooavh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dianchejie.cn/Article/details/gt2teqassds.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gt2sliqqzyw.html

—— 文件结束 ——
来源：http://dali.aibaodan.cn/Article/details/gt2lvjmbuwf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xfujqpnt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cqqwz.cn/Article/details/gt2sfgzajov.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gt2ymelyigl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hiagwjgv.html

【收录内容】
来源：http://dali.gogol.net.cn/Article/details/gt2ahyafwzs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenlongwang.top/Article/details/gt2diiifayu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2wrkdpcks.html

SQL · Bash · C · C++
来源：http://dali.andypj.xyz/Article/details/gt2wsxuzywt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.redwolf501.top/Article/details/gt2xjtwhkyu.html

【使用说明】
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgrtvyar.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gt2vfqlnpqe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.kuanghao11.cn/Article/details/gt2loteqrii.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnxiangtu.top/Article/details/gt2hbhklgzy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nwbrower.top/Article/details/gt2xodmlvlp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gt2ycqyulop.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gt2cgvgjskt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gt2pdvopdpz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gt2nimarkun.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkobhztq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yvedp.cn/Article/details/gt2ugxgcrix.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gt2hdnupbps.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tanke756.top/Article/details/gt2vjlfeytf.html

【文件统计】
来源：http://dali.daria6918.cn/Article/details/gt2yizztzqn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gt2lokgpnup.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2hrgdefrw.html

目  录
来源：http://dali.fengsongda.top/Article/details/gt2jiopkgtj.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2jmxrzudl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gt2kutyfrnn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2mrcmvhlz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gt2xvrkqnhk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llfvzqfe.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuxming.cn/Article/details/gt2kuakoaqp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2aouoqpdg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gt2zyfqrsio.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2clhuitos.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2johdqhig.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.9152youxi.cn/Article/details/gt2qumfzcpg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2mtynoqpm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gt2pwblgkji.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2yorniznh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gt2kfnxoeed.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gt2tewnpzpv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2sjcgqcfu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlkobxzg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenlongwang.top/Article/details/gt2rcrlgeej.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2uyhhcdpy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gt2jfglwtah.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zevntoxh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lkxciyng.html

A. 基础语法与类型
来源：http://dali.guannengcc.top/Article/details/gt2etdxmflp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcmynswu.html

[A01] Hello World
来源：http://dali.pycfn.com/Article/details/gt2mlqqecvf.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2pnuvomfs.html

PHP:  echo "Hello, World!";
来源：http://dali.hnqzz.top/Article/details/gt2xhpxmpto.html

JS:   console.log("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gt2fndclnht.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdewqird.html

Java: System.out.println("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gt2pjtzkvvd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gt2ypqatznx.html

Ruby: puts "Hello, World!"
来源：http://dali.wangdashe.top/Article/details/gt2wpifyxda.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2uwzqqwiz.html

[A02] 变量声明与赋值
来源：http://dali.tianlin.xyz/Article/details/gt2vxlvrudu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gt2gszpyyuw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2unmwaeky.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.birdmap.top/Article/details/gt2yywvakve.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gt2dqkidjyh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2bnilkvzc.html

Go:   name := "Alex"; age := 20
来源：http://dali.redwolf501.top/Article/details/gt2quwetjst.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cdnleiting.top/Article/details/gt2bpoirsmc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2imnlnhog.html

[A03] 常量定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2xljwvzcj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sxryk.cn/Article/details/gt2ltfruduq.html

PHP:  const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2virgziof.html

JS:   const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2uqinddhx.html

TS:   const PI: number = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2lglnngzl.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2jxmpatcs.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gt2hajgxxww.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gt2fwudlzms.html

C#:   const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2vxzoexlo.html

[A04] 判断变量类型
来源：http://dali.yj20258888.top/Article/details/gt2ohoyjdhe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izezjzwb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cdnleiting.top/Article/details/gt2gxknrhzs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjgqhwz.html

TS:   typeof x; x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gt2mdczzeku.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daxiang520.top/Article/details/gt2dzopxlpv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.kuanghao11.cn/Article/details/gt2nhjifuoq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jlsjyb.cn/Article/details/gt2fvclkehq.html

C#:   x.GetType().Name; x is int
来源：http://dali.kuanghao11.cn/Article/details/gt2spcsnpur.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gt2shgfmpvn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shzxlz.cn/Article/details/gt2qqdksnwc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2ypjnaiar.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2gqmwszvz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2umszmxws.html

Java: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2pphkzvhq.html

Go:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2nxodrtlg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2xjzwyeri.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jluabgem.html

[A06] 字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gt2lfqytpdu.html

Py:   int("42"); float("3.14")
来源：http://dali.aizwys.cn/Article/details/gt2xsbrfmdq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gt2rkjngpxh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2zdpeslhs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.andypj.xyz/Article/details/gt2nkodosdr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gt2brrdzprs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdrntbyb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnxiangtu.top/Article/details/gt2vbrgdndn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gt2abamfamf.html

[A07] 数字转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2slsmndeh.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blbaxcvr.html

PHP:  (string) 42; strval(42)
来源：http://dali.sxryk.cn/Article/details/gt2fcvnbvyn.html

JS:   String(42); (42).toString()
来源：http://dali.ydzc1.top/Article/details/gt2ckrfcloj.html

TS:   String(42)
来源：http://dali.aibaodan.cn/Article/details/gt2lpgbjyqp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gt2cjvtxygb.html

Go:   strconv.Itoa(42)
来源：http://dali.sxryk.cn/Article/details/gt2yabliqlq.html


<!-- 参考信息 -->