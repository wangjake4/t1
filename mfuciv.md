代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gtrfgvrmyb.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gtprwhjtaq.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtbohxrtfd.html

print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtzssiqstz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gtdjkmaquv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxinkj.top/Article/details/gttuojjhhj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtlokgrvih.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtjbmiryjs.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gtsmfwjsyg.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gtvgazdamh.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtydgvklbl.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtglvnlgnq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangdashe.top/Article/details/gtxvbhryhw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtovuqjrwi.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtusilcfrn.html

?string $name = null
来源：http://dali.jianghu66.top/Article/details/gtjkitezoq.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtqmsern.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtyzjrugbj.html

[U48] PHP：纯枚举
来源：http://dali.sweek.top/Article/details/gtmkzpzgkw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gtzdrzbhvp.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gtdnstckgv.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtufttowwt.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gtjwaahgmu.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gtinxuevja.html

[U51] PHP：数组解构
来源：http://dali.hongshengwenyu.top/Article/details/gtixknmpmv.html

[$a, $b] = $arr;
来源：http://dali.dashuyun.cn/Article/details/gtaqvdecbe.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxysoddv.html

$double = fn($x) => $x * 2;
来源：http://dali.xziqi.cn/Article/details/gtxkkaqnfq.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtfqzhiadf.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gtmqoepuml.html

[U54] PHP：空安全调用
来源：http://dali.yonumen.top/Article/details/gtdxxhasqx.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gtomgeeylm.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gtaynebmpo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fengsongda.top/Article/details/gtoenwxmrx.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtldibwvyg.html

f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtsyjmytls.html

[U57] PHP：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gteutxxbem.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gteadrxocn.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtgulqpofg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtrrrskufg.html

[U59] PHP：自定义排序
来源：http://dali.gzhubu.top/Article/details/gthiuuoiyg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtpsqesysg.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gtooxascyw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gtgfdrgyjk.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gtlmqxwfyn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtbqaoebsd.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gtiahinbnk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gtmoqpyjyl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtnjrsfsev.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gttplyipqv.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtepmrfasz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aibaodan.cn/Article/details/gtnpjpxhpd.html

[U65] PHP：会话
来源：http://dali.xziqi.cn/Article/details/gtgxeyzydb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtznrebups.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gtmqfkunei.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtajvymkuv.html

[U67] PHP：处理文件上传
来源：http://dali.yvedp.cn/Article/details/gtqpmgtcgv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuxming.cn/Article/details/gtzischoof.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtiowpakcx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sweek.top/Article/details/gtfwtkuyoj.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyztfwja.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gtdvdokmev.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtwbuoqjzb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuetiantiany.cn/Article/details/gthsyylfum.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtpraanfqf.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtqhxiurfp.html

[U72] PHP：写错误日志
来源：http://dali.chenzaomai.com/Article/details/gttiglctzq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gtplbebpih.html

[U73] PHP：读取 ini 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtouemujvz.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gtjveiumhl.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gttvjpdxqh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gtomvzucat.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gtjmlzwmto.html

composer require psr/container
来源：http://dali.pycfn.com/Article/details/gtvgdkmshq.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gteevhaojw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgufenzy.top/Article/details/gtdzqneavd.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gtrngygdxh.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtmqhtqdqd.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtjfpbuype.html

composer require --dev phpunit/phpunit
来源：http://dali.nwbrower.top/Article/details/gtenfaktgn.html

[U79] PHP：静态分析
来源：http://dali.vqdsnc.cn/Article/details/gtlzqowdlz.html

composer require --dev phpstan/phpstan
来源：http://dali.yuanzhike.top/Article/details/gttowrfbfu.html

[U80] PHP：代码规范修复
来源：http://dali.meibo888.top/Article/details/gtvccowlra.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.meibo888.top/Article/details/gtmkduehyj.html

[U81] JS：初始化项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbooithv.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gtoziirqvw.html

[U82] JS：package.json 脚本
来源：http://dali.0kj1m.cn/Article/details/gtkytaybqt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yongpay.top/Article/details/gtucvwakxo.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj20258888.top/Article/details/gtwsplxtgm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtdnqbmwzi.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gtcrpqottm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daria6918.cn/Article/details/gtdysynajt.html

[U85] JS：可选链
来源：http://dali.cashguo.top/Article/details/gtcpdrxbzr.html

a?.b?.c
来源：http://dali.ppjwa.cn/Article/details/gttgkoifst.html

[U86] JS：空值合并
来源：http://dali.jqgufenzy.top/Article/details/gtkfhuhfwv.html

a ?? b
来源：http://dali.daria6918.cn/Article/details/gtuvgmaiub.html

[U87] JS：解构默认值
来源：http://dali.yuxming.cn/Article/details/gtvjkffykx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sysykeji.top/Article/details/gthxhngfmk.html

[U88] JS：对象展开合并
来源：http://dali.redwolf501.top/Article/details/gtfapimrzc.html

{ ...a, ...b }
来源：http://dali.chenzaomai.com/Article/details/gtsjxdfchh.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gtxqxvdjox.html

[...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtsqwcyion.html

[U90] JS：数字数组排序
来源：http://dali.hfpthk.cn/Article/details/gtmtkrhabc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtxafzclly.html

[U91] JS：对象键值遍历
来源：http://dali.guannengcc.top/Article/details/gttthblyen.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.mhx1999.top/Article/details/gthyyowsrd.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gtlhsfvits.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtfvhdfvtr.html

[U93] JS：模板字符串
来源：http://dali.nanxuanxn.top/Article/details/gtyrjsfzgj.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gtwdfxjsrg.html

[U94] JS：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gttnjspdvc.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtiwtvssvc.html

[U95] JS：Promise 包装
来源：http://dali.pycfn.com/Article/details/gtgqbbarhy.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gthbnowtta.html

[U96] JS：async/await 与异常
来源：http://dali.ivvv.top/Article/details/gtqeksjywf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gteoznvvtg.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtpguhtvhw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwzpabby.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenlongwang.top/Article/details/gtopreqsxf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hysaishi.cn/Article/details/gtsuorvinv.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gtcxeptuom.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gthvalcdwk.html

[U100] JS：DOM 查询
来源：http://dali.sweek.top/Article/details/gttavtyjqy.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjslwasd.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gtzxwonzvd.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gtcnevures.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtnauvtzev.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guowangkeji.top/Article/details/gtyhpojljf.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gtrmmndjwh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtzxfpcuaf.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gtketmfuey.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtxemgzgxg.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gtgazrbwmj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gtselgscpb.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtktkshdoe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gtzgpeancv.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gthicfspsx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtstnpqbib.html

[U108] JS：随机整数
来源：http://dali.pengpengdd.cyou/Article/details/gtgnwbxsvg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gtqqadijdl.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gthdrjxkjh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtphdhpmpi.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gtehocfygc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yongpay.top/Article/details/gtltbuxvxd.html

[U111] JS：对象转 Map
来源：http://dali.jqgufenzy.top/Article/details/gtsglhqnhi.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gtnagiheft.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtrkhetdvj.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtkavpskbm.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtgzbwphtp.html

s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtaluuqlho.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrgdfqxc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gtkeddmusj.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtczxhcsqx.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtfkegkjqc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gttsgpszek.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gtebitkgxg.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtvxvhkiof.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gtanvwmfly.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqcxjtfr.html

npm i -D vite;  npx vite
来源：http://dali.sxryk.cn/Article/details/gtlwqrhdbu.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtekbtzfrf.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gtfwjlavbq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hfpthk.cn/Article/details/gtoewufahe.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtoctiwpiy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlfcdnasb.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtqrcrbsri.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfokwhcnu.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gttbfpncpl.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawbhdheh.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gtjjahcagb.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtplhibtvv.html

TypeScript ..... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwwpchju.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gtjsbznkfi.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtsrcizjyi.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtzsyqsozz.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gttrbvnpec.html

C .............. 30
来源：http://dali.ybcxt.top/Article/details/gtigjwjmab.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gtktutkefq.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gtqxhkllmd.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gtjelkvvtt.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gthwtgljtm.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtauelzkfg.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gtwflkfjxo.html

Perl ........... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixhmfsjk.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvogxpmv.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtgjasnwzf.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gtpclawzsq.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gtiaxsdtyb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtlxlmhmza.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gthiyedbai.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtlvimuzmv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtwrvxsaak.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdxsveau.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtqwqhzkou.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtiahsuutq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtxrsahxgq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtkoucvaoa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtlnxtnexu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtudbbrcwy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtimxlnyis.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwugdvss.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaepmszgc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gtxcjblhmu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gttcoitniz.html

Q SQL 专题                              90
来源：http://dali.316326.xyz/Article/details/gtxdhrfpue.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gtfrcjszni.html

S C / C++ 专题                          60
来源：http://dali.cucudq.cn/Article/details/gthqovjtfu.html

T 其他语言补充                          60
来源：http://dali.daxiang520.top/Article/details/gtpatnzbwk.html

U 高频实用片段                         120
来源：http://dali.yanxiufei.cn/Article/details/gtqogebbry.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gttzmgoaxr.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gttjkjnmjk.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkapxlpky.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gtgwvnrshz.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtlqphrvdh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cucudq.cn/Article/details/gtbkdizdnn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangshuangyany.cn/Article/details/gtuctfhpdo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gttcfhwbmy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cheryme.top/Article/details/gtakvukbqz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gtgbjolosu.html

—— 文件结束 ——
来源：http://dali.zdqjudy.top/Article/details/gtrtbfxuyw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpyasnjht.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gaohongyu789.top/Article/details/gtlkjiprsg.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gtrtllmbub.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttmguarzh.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gtxgyhimds.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gtqmpxwnpn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cucudq.cn/Article/details/gtawpapbbs.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gtyozernfm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtbnbczivq.html

【使用说明】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuenqefx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zycfv.cn/Article/details/gtnnyzlfax.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.iojbl.cn/Article/details/gtepkepimh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.feifeiyinyue.top/Article/details/gtujgqqzas.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guowangkeji.top/Article/details/gttiarrpqd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gtxnfvkydg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjojevhiv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yanxiufei.cn/Article/details/gtvicqqwwi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gtmtzcixox.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtvhcycpyi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnqzz.top/Article/details/gtuimusipc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gtmtcuyitc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gttyzrjztf.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtuhxoattr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zdqjudy.top/Article/details/gtakzdbtwe.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtiaiztghf.html

目  录
来源：http://dali.tanke756.top/Article/details/gtdhwelfiy.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtcjglvlfd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnluzvogf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnjfitov.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtgyixfgcy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gthgnqngdc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtczyfdmii.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtrczaxxsh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtlzjukhka.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gteiarpjxd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtmraydvbv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtspioxram.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtsrpdinxf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtshxbuoyh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtvrznutjd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.0kj1m.cn/Article/details/gtsfptfkad.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gzhubu.top/Article/details/gtapinefcb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtlqqlozwr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.0kj1m.cn/Article/details/gtzsrsaigz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tian-w.cn/Article/details/gtkwoikxev.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guowangkeji.top/Article/details/gtqkcazcxh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtcdiqxifc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtitudpewj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthhqvcrzr.html

A. 基础语法与类型
来源：http://dali.0kj1m.cn/Article/details/gtwgufszzz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtshgaxmzi.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiahbztf.html

Py:   print("Hello, World!")
来源：http://dali.0kj1m.cn/Article/details/gtjcmajdoi.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258888.top/Article/details/gtlrujiifb.html

JS:   console.log("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtuosgtalw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gtohgiixji.html

Java: System.out.println("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtsxhtuqur.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtejhjbkgp.html

Ruby: puts "Hello, World!"
来源：http://dali.birdmap.top/Article/details/gtfrydjljb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gttjqmsjis.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgxadrzg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gtzfuiarch.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.fzhhl.top/Article/details/gtdwqtefda.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtcwogldjk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gtfblgaetm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtuvqpcnxq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyqmmidj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gtfinvbdcb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gthfybsngz.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gtqtnhawhv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gtrdeojtpy.html

PHP:  const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtcsfqudxl.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gttnjbroml.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtqglrzsoa.html

Java: static final double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtsbdvoffz.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtmxrhejpb.html

Ruby: PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtjinumvyf.html

C#:   const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtsdqdakgg.html

[A04] 判断变量类型
来源：http://dali.c1oappe.top/Article/details/gtcbybcjrg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gtwxvcmnkv.html


<!-- 参考信息 -->