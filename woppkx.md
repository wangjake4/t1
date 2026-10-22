代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cftwgush.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psvfpkyq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gt2mgoeefgc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gt2iirbdliy.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gt2ojtugoft.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gt2slmvmyad.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigufen.top/Article/details/gt2zeaxnbsx.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gt2ycfaxzeq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gt2joyxlmjc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2fkwonzqp.html

[U46] PHP：可空类型
来源：http://dali.guowangkeji.top/Article/details/gt2mjxfiyym.html

?string $name = null
来源：http://dali.jianghu66.top/Article/details/gt2fgyorzpo.html

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gt2macjdogf.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gt2zjvlcbqz.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skmaiwrn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sysykeji.top/Article/details/gt2hixzhxau.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctjcshpt.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldzuogdv.html

[U50] PHP：构造器属性提升
来源：http://dali.nwbrower.top/Article/details/gt2xcxtrxfi.html

public function __construct(private int $id) {}
来源：http://dali.hfpthk.cn/Article/details/gt2lxjwrqau.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gt2fjpmvvcm.html

[$a, $b] = $arr;
来源：http://dali.ivvv.top/Article/details/gt2vvpesxag.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnsjuijz.html

$double = fn($x) => $x * 2;
来源：http://dali.tanke756.top/Article/details/gt2rewqhflo.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gt2gwucxefj.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gt2hwtsinur.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gt2vqjoicqw.html

$obj?->method()
来源：http://dali.jinqigufen.top/Article/details/gt2cbrlhqpk.html

[U55] PHP：match 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ojrszpgh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2mndylyca.html

[U56] PHP：命名参数
来源：http://dali.yanxiufei.cn/Article/details/gt2ohnanpat.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2kmuowvim.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2jmkoioyp.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2btkfppwp.html

[U58] PHP：数组三件套
来源：http://dali.dianchejie.cn/Article/details/gt2surimold.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gt2ndatamcp.html

[U59] PHP：自定义排序
来源：http://dali.tanke756.top/Article/details/gt2gvsxtpuk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2crapkrma.html

[U60] PHP：JSON 编解码
来源：http://dali.cashguo.top/Article/details/gt2gvtprpjo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guowangkeji.top/Article/details/gt2vwwzbpxe.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gt2uzzlnbju.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2cvmjqssy.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gt2qskaepxy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwwcrilx.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gt2gmvrzwrx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.bjfxy.top/Article/details/gt2yxympfsk.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gt2uzgyabja.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gt2jnwdtiyr.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gt2utpobupv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2ljzarzid.html

[U66] PHP：设置 Cookie
来源：http://dali.shzxlz.cn/Article/details/gt2mreefmgi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2elgjyrpx.html

[U67] PHP：处理文件上传
来源：http://dali.shangyingyoupin.top/Article/details/gt2wccncyrn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gt2efgeqdmd.html

[U68] PHP：PDO 连接
来源：http://dali.jyoumei.cn/Article/details/gt2bwrhwbdu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gt2lyadsxja.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqkjjgiz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gt2glvwiked.html

[U70] PHP：PDO 事务
来源：http://dali.shzxlz.cn/Article/details/gt2brqihqfj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuanzhike.top/Article/details/gt2rbzjcvor.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2foccglot.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2fkxbadat.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2cayxxabu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.birdmap.top/Article/details/gt2phspkoaw.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gt2nepfwkiy.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjypdmtt.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrahtcyn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gt2eswxtdjv.html

[U75] PHP：依赖注入
来源：http://dali.fzhhl.top/Article/details/gt2ggdjuzgd.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gt2ktzizprg.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umytcffa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.bjfxy.top/Article/details/gt2tpplrcop.html

[U77] PHP：模板渲染
来源：http://dali.yangfankeji.com/Article/details/gt2xmyhtkdw.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gt2agfjpfpk.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnxhmjnw.html

composer require --dev phpunit/phpunit
来源：http://dali.zycfv.cn/Article/details/gt2kxxpnrrj.html

[U79] PHP：静态分析
来源：http://dali.ehwqpu.com/Article/details/gt2zqgkcdiz.html

composer require --dev phpstan/phpstan
来源：http://dali.bjfxy.top/Article/details/gt2epghzyam.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcbdrkjl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yueranfly.top/Article/details/gt2xamaoboc.html

[U81] JS：初始化项目
来源：http://dali.yanxiufei.cn/Article/details/gt2uvuyqraf.html

npm init -y;  npm i express
来源：http://dali.yvedp.cn/Article/details/gt2yyivhnti.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gt2yrctiupl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gt2qpcekobo.html

[U83] JS：ES Module 导入导出
来源：http://dali.yongpay.top/Article/details/gt2wnczthej.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2zrnzgghn.html

[U84] JS：CommonJS 写法
来源：http://dali.kuanghao11.cn/Article/details/gt2ipogkaxr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuxming.cn/Article/details/gt2sijcihju.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gt2vpusccjz.html

a?.b?.c
来源：http://dali.yanxiufei.cn/Article/details/gt2vsemgenj.html

[U86] JS：空值合并
来源：http://dali.guowangkeji.top/Article/details/gt2huumergs.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gt2iqjozbah.html

[U87] JS：解构默认值
来源：http://dali.dashuyun.cn/Article/details/gt2vkpsdryn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xylfe.cn/Article/details/gt2omzmpdjh.html

[U88] JS：对象展开合并
来源：http://dali.9152youxi.cn/Article/details/gt2ndfvzjgt.html

{ ...a, ...b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgjmfuqw.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gt2alwtznji.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2oqzdyssy.html

[U90] JS：数字数组排序
来源：http://dali.9152youxi.cn/Article/details/gt2hhaohyno.html

[...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2phxwzutd.html

[U91] JS：对象键值遍历
来源：http://dali.dianchejie.cn/Article/details/gt2xgmocjkh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ehwqpu.com/Article/details/gt2gchnpkrp.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbbflrfn.html

structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2exwjhuym.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gt2wisznpnd.html

`共 ${n} 条`
来源：http://dali.yangfankeji.com/Article/details/gt2akihkpkv.html

[U94] JS：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gt2cxibxvum.html

const double = x => x * 2;
来源：http://dali.shzxlz.cn/Article/details/gt2xlwopojg.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gt2czuxbirc.html

new Promise((resolve, reject) => {})
来源：http://dali.fzhhl.top/Article/details/gt2tgmaybyj.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gt2gbhpuzgw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nuvajkyd.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gt2vfnwicle.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2xqoivoiz.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gt2hzlpjxib.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gt2tyahsyox.html

[U99] JS：事件监听
来源：http://dali.nanxinkj.top/Article/details/gt2iisvrtib.html

el.addEventListener("click", e => {})
来源：http://dali.yvedp.cn/Article/details/gt2hfgefzid.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gt2exfllwcs.html

document.querySelector(".item")
来源：http://dali.yueranfly.top/Article/details/gt2nhvivvns.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gt2qoytndee.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gt2fvjezwfb.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sisekysu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gt2nlzgntel.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gt2qbhxnmxq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpopbelq.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gt2vvcmauqz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2yroyidtl.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gt2dukejama.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.svipenyu.cn/Article/details/gt2qlprpaob.html

[U106] JS：日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2onchdjoa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbywxokm.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gt2vfbjsmfe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gt2mlsczker.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gt2shhqhzje.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.birdmap.top/Article/details/gt2sreuwooj.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypekjhrh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2ighlnskc.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gt2lputanrp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gt2lqsecqzp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2epxxrdwx.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2maqcbufw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkcxvaz.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2uhrwyovt.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gt2xzaglmtg.html

s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsesyrxu.html

[U114] JS：JSON 深比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2fraacivb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gt2egymqnxk.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2zusjbwfq.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2nfpqvsve.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jlsjyb.cn/Article/details/gt2jmrhapxw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfccobry.html

[U117] JS：单元测试
来源：http://dali.sufxvd.cn/Article/details/gt2pewchnmm.html

npm i -D vitest;  npx vitest
来源：http://dali.shuidangran.top/Article/details/gt2heacyjyg.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gt2xhqiiczk.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gt2rfwanxft.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gt2isdldgau.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gt2htklslxv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gt2xctspffz.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gt2fhpkopgp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2klnnthsh.html

统计汇总
来源：http://dali.yj202588.top/Article/details/gt2uahzonna.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ntdyicwp.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yenvlhnq.html

Python ......... 252
来源：http://dali.jianghu66.top/Article/details/gt2gfnybgms.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuaqorwo.html

JavaScript ..... 252
来源：http://dali.yj202588.top/Article/details/gt2vejhufpz.html

TypeScript ..... 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2atjjqfyd.html

Java ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2uxpphhvp.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gt2hgurgqvc.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gt2lgcrnwix.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sropcenj.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gt2ihzalwvg.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gt2fuybhitr.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gt2hfiaphue.html

Bash ........... 80
来源：http://dali.jyoumei.cn/Article/details/gt2xhuqxriq.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2ritvzdus.html

Swift .......... 15
来源：http://dali.jqgfzy.top/Article/details/gt2abaynwmc.html

Lua ............ 10
来源：http://dali.yj202588.top/Article/details/gt2vyultdib.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gt2cofbpjfn.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gt2vwtrvrow.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2cahqjjsc.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gt2mstwfowr.html

按章节统计：
来源：http://dali.hfpthk.cn/Article/details/gt2axobjvta.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2ixssgdrc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2zxppkfew.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stlqungy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2fkpickqh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gt2gnrqgqty.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gt2qrexuksy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2hofystis.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gt2tkpzyhwq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2pxyppbnb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gt2hyrbbodn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2icljkaox.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkfgxrxn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2rhavnkvf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gt2xcyshfns.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gt2diwtfhyb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgcdgnvb.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nelumnit.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gt2mewyzdxz.html

S C / C++ 专题                          60
来源：http://dali.redwolf501.top/Article/details/gt2awyblczb.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gt2ixxjzalr.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gt2rqjasmjw.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfswxbwh.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gt2asqfsmnj.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2ltagkxfa.html

使用提醒
来源：http://dali.guowangkeji.top/Article/details/gt2kexbbzrt.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2qmgcuoms.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gt2sjdorwwh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gt2ajuleqkd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gt2onyzmmds.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gt2wrjawqwz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gt2mqzmkzep.html

—— 文件结束 ——
来源：http://dali.9152youxi.cn/Article/details/gt2cqfelfdn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wwlozyec.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gt2ajhftfbm.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gt2gfvrwczh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxctrqbz.html

【收录内容】
来源：http://dali.tanke756.top/Article/details/gt2lqufgngj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gzhubu.top/Article/details/gt2sindykbi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hywenlv.cn/Article/details/gt2oznhhonm.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gt2uyqkoftq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwvvfqol.html

【使用说明】
来源：http://dali.cucudq.cn/Article/details/gt2ksdifrqf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmlxnoco.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sysykeji.top/Article/details/gt2kztfhdtf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gt2lgyrczok.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gt2zicydejl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gt2sxgyabks.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fengsongda.top/Article/details/gt2sufyyeib.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gt2ekghwize.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.redwolf501.top/Article/details/gt2gcozkxss.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gt2zqlrmqvr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gt2irpcuedz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yanxiufei.cn/Article/details/gt2sbpbudlx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gt2qizdiyrd.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gt2nzqbuzgj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gt2nlqauytr.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2iqqntjyf.html

目  录
来源：http://dali.ppjwa.cn/Article/details/gt2tuwmcmqg.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2isiewxyz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gt2tqjmkiwz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gt2txllfziq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gt2aoxuiywf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gt2mwakwxia.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cucudq.cn/Article/details/gt2tzeqzmbn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gt2dwokrxpf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nodtqnda.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmuynsaq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2jqtnsugy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gt2hjmvmmfl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2vrpymxwy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndjhnawi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2thrpusxo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gt2zgmlmnfr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cdnleiting.top/Article/details/gt2kgqoywaq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2ajngbjwt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guowangkeji.top/Article/details/gt2barisgph.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2irvikgrf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gt2jqqqydim.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2qplqqvpb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gt2omfxjcwf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2khgszynb.html

A. 基础语法与类型
来源：http://dali.gogol.net.cn/Article/details/gt2zhoopbon.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ieppxytu.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gt2cjxgoqhw.html

Py:   print("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gt2jcohgsnu.html

PHP:  echo "Hello, World!";
来源：http://dali.yonumen.top/Article/details/gt2rjqznojt.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrpxkrbo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gt2zkjlxnjr.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gt2gdhryhds.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gt2ybrhssip.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gt2cgofkkyo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gt2utnszeqv.html

[A02] 变量声明与赋值
来源：http://dali.hywenlv.cn/Article/details/gt2ivojlufd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cucudq.cn/Article/details/gt2zuvjwufz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nwbrower.top/Article/details/gt2efwjnxrd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2wfvzdqqq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seaiauit.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gt2mnlttzjx.html

Go:   name := "Alex"; age := 20
来源：http://dali.sufxvd.cn/Article/details/gt2mbqlaqrk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbkdmxsy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gt2qasstvcc.html

[A03] 常量定义
来源：http://dali.zhengqikj.top/Article/details/gt2ljevqykp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgufenzy.top/Article/details/gt2fotnjdfm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2ovylfmcf.html

JS:   const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2ewxpkauk.html

TS:   const PI: number = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2lpldauay.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2fisjczva.html

Go:   const PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gt2ssgsfilj.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gt2dnnacard.html

C#:   const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2zknxivzk.html

[A04] 判断变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2lqpextbu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ivvv.top/Article/details/gt2ercybqba.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.quarkkingdee.top/Article/details/gt2lapewjzb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gt2ulvdhwei.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gt2diestcht.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cheryme.top/Article/details/gt2koggoslx.html


<!-- 参考信息 -->