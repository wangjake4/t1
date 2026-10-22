代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gt2uqgnsfjz.html

sys.stdout.isatty()
来源：http://dali.jyoumei.cn/Article/details/gt2zrjbnewf.html

[U40] Py：打印到标准错误
来源：http://dali.jlsjyb.cn/Article/details/gt2oiephqrt.html

print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gt2jntlkaib.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yangfankeji.com/Article/details/gt2lddhzbmu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gt2btjrmweh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gt2hynrusqv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gt2gweugfpz.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2uabidxvx.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gt2edoqsrgh.html

[U44] PHP：开启严格类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpwnfpni.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gt2zkkzwpyd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.meibo888.top/Article/details/gt2wmiywcgz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2eeoldjpg.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ywxqjngn.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gt2zjwtcjhr.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gt2isnvjkwg.html

int|string $id
来源：http://dali.yvedp.cn/Article/details/gt2zyxmwbxx.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gt2cbjrvrqu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gt2zoguqita.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnundkwc.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gt2qmcoqkqe.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gt2taswkolr.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gt2akfwpncf.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gt2qhdhrbxr.html

[$a, $b] = $arr;
来源：http://dali.shuidangran.top/Article/details/gt2tijytcfe.html

[U52] PHP：箭头函数
来源：http://dali.fengsongda.top/Article/details/gt2bgwjyfza.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2aerizabf.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gt2lccvjuuk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gt2czxextvg.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gt2piswezog.html

$obj?->method()
来源：http://dali.0kj1m.cn/Article/details/gt2ynradgwe.html

[U55] PHP：match 表达式
来源：http://dali.c1oappe.top/Article/details/gt2dyilgucl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gt2wrjakmaf.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2chmtvqam.html

f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2kkpmcwst.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2rgkqmrzj.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gt2shmfrzhu.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gt2nttsnkiz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2omolxfig.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gt2dpcpooxs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gt2bxiczlzz.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gt2sdfvgzzz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqindjax.html

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gt2flzkkynv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2shyqmgph.html

[U62] PHP：日期对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eyrcwwhy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gt2btydbdtu.html

[U63] PHP：文件读写
来源：http://dali.nwbrower.top/Article/details/gt2lddhvaot.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yongpay.top/Article/details/gt2uptvlcbj.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umzcpojx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gt2okrjrovt.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gt2vrehprjp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2qzbxvzfk.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gt2cdiosjbg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.andypj.xyz/Article/details/gt2soswrlhd.html

[U67] PHP：处理文件上传
来源：http://dali.guowangkeji.top/Article/details/gt2njfxiwbw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gt2tspepczq.html

[U68] PHP：PDO 连接
来源：http://dali.xziqi.cn/Article/details/gt2pfcjyyfl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gt2xcrltbei.html

[U69] PHP：PDO 预处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwgokdxj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yueranfly.top/Article/details/gt2fupyqncj.html

[U70] PHP：PDO 事务
来源：http://dali.cashguo.top/Article/details/gt2whrbjpak.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gt2pbqqgecn.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amerfumg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2zcghqexp.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gt2rlvikprl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.birdmap.top/Article/details/gt2jhsjbnnc.html

[U73] PHP：读取 ini 配置
来源：http://dali.cqqwz.cn/Article/details/gt2benhbsin.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gt2uzesifrv.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2yhefmish.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gt2wkiovdsw.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gt2qfhinxqp.html

composer require psr/container
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbcjqsde.html

[U76] PHP：简单路由
来源：http://dali.9152youxi.cn/Article/details/gt2gmqfamma.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gt2zsaqngqr.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gt2klwlbumv.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gt2zauvyqdg.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gt2akfltusa.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kheypqgd.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gt2cshhtjed.html

composer require --dev phpstan/phpstan
来源：http://dali.iojbl.cn/Article/details/gt2llgkcema.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gt2bvacykxc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gt2vbbikisx.html

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gt2lfzlnzqj.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gt2ohgsnjli.html

[U82] JS：package.json 脚本
来源：http://dali.yangfankeji.com/Article/details/gt2acqbigiv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xziqi.cn/Article/details/gt2xhizjhdi.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gt2esmlpiki.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gt2wyugfazb.html

[U84] JS：CommonJS 写法
来源：http://dali.hnxiangtu.top/Article/details/gt2hbymirvk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gt2dmxbsqfu.html

[U85] JS：可选链
来源：http://dali.bjfxy.top/Article/details/gt2yudivfqf.html

a?.b?.c
来源：http://dali.quarkkingdee.top/Article/details/gt2lkdhzisn.html

[U86] JS：空值合并
来源：http://dali.jqgfzy.top/Article/details/gt2gysculsd.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gt2njjqlgoe.html

[U87] JS：解构默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2vpjknckj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcanlpzw.html

[U88] JS：对象展开合并
来源：http://dali.gaohongyu789.top/Article/details/gt2rfckrmho.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gt2gbdopxkt.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gt2aaoqzrur.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2mfpxkrst.html

[U90] JS：数字数组排序
来源：http://dali.dianchejie.cn/Article/details/gt2jwebquin.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2fxbywvei.html

[U91] JS：对象键值遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2gfcqdvsj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenzaomai.com/Article/details/gt2dnoujcha.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gt2udbgnrir.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2eyqkdkoe.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gt2lkxnukqv.html

`共 ${n} 条`
来源：http://dali.yueranfly.top/Article/details/gt2lasbufth.html

[U94] JS：箭头函数
来源：http://dali.zycfv.cn/Article/details/gt2vczryhmy.html

const double = x => x * 2;
来源：http://dali.hnqzz.top/Article/details/gt2yrluymxp.html

[U95] JS：Promise 包装
来源：http://dali.xuanzx.com/Article/details/gt2mqwmgmia.html

new Promise((resolve, reject) => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjlkfjyh.html

[U96] JS：async/await 与异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnsotequ.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2fwncuzcy.html

[U97] JS：并发请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixxlwbnw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2cnsxertk.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gt2qabzjrvc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gt2dnvmxjsc.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gt2ftrwbnmj.html

el.addEventListener("click", e => {})
来源：http://dali.wangdashe.top/Article/details/gt2qygxlmiy.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gt2tzrquozs.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2zmmqreys.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gt2cjhvrktf.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gt2yqbcxlac.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gt2lymahjkb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jlsjyb.cn/Article/details/gt2hjaspdlj.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gt2wkhznuhc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gt2ilwcitaj.html

[U104] JS：防抖
来源：http://dali.ehwqpu.com/Article/details/gt2jwylevms.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2mpmhkutw.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gt2dksyjpjk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gt2ylfxtjte.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2snipuuvh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gt2zmnxzhzt.html

[U107] JS：数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2lumauzxs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2ahcmhqwn.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gt2wqjpelrf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gt2uobznrni.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gt2bvvbpmkl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2drvubycd.html

[U110] JS：数组分块
来源：http://dali.tian-w.cn/Article/details/gt2syubsplr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gt2lwahszks.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gt2vxzqbhis.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2helpicnx.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upcvfdov.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2wrtltoqh.html

[U113] JS：正则替换全部
来源：http://dali.nanxuanxn.top/Article/details/gt2fqcjajwy.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2gxqaeong.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gt2zgrcxqtc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gt2bhnwywjq.html

[U115] JS：生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gt2gjcurxih.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2qbvojvcb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gt2gqrcgmgz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gt2pbvzyttq.html

[U117] JS：单元测试
来源：http://dali.tianlin.xyz/Article/details/gt2zsdzfnkx.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gt2grhseihc.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gt2dykicsrw.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gt2cfnzizbq.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gt2yjuxhqnt.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gt2pblpstag.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gt2ynzqnbnn.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gt2guqstmso.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2unjqzhzx.html

统计汇总
来源：http://dali.feifeiyinyue.top/Article/details/gt2okmiikjl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wesgzsie.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2qrqkojma.html

Python ......... 252
来源：http://dali.wangdashe.top/Article/details/gt2hbfggrab.html

PHP ............ 252
来源：http://dali.nanxuanxn.top/Article/details/gt2rvlodjxs.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gt2qjpcycal.html

TypeScript ..... 212
来源：http://dali.sufxvd.cn/Article/details/gt2amzoawhp.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gt2kmasioby.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gt2sqvahcek.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2leqnutot.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gt2dyojloam.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gt2sguxgrca.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gt2outyzazi.html

SQL ............ 90
来源：http://dali.ybcxt.top/Article/details/gt2otxsnrpl.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gt2gzzrxiol.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gt2uzftbgci.html

Swift .......... 15
来源：http://dali.yvedp.cn/Article/details/gt2rrlcjfqj.html

Lua ............ 10
来源：http://dali.jyoumei.cn/Article/details/gt2bhwdusic.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gt2uiqfjosi.html

Scala .......... 10
来源：http://dali.shuidangran.top/Article/details/gt2cixbmnez.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2dbkancpz.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gt2oixyrtgj.html

按章节统计：
来源：http://dali.gogol.net.cn/Article/details/gt2dynnelmw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gt2vfgvwcgy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gt2hixbfset.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2pdeuubgq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdwyfeqw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gt2ptoluhgw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gt2pwiqzdwr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gt2lehlqddc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gt2yxjvmehs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gt2efuocqlt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2daduwfeu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2kywqwqxf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2xmyaewbj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2glcqtuyv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gt2oggawycw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gt2cfiozeyk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2owhyugah.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gt2odsvvrjm.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihisfiez.html

S C / C++ 专题                          60
来源：http://dali.c1oappe.top/Article/details/gt2vqrotfak.html

T 其他语言补充                          60
来源：http://dali.guowangkeji.top/Article/details/gt2opsjzxsv.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gt2itdmacqk.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2buimcxnm.html

合计                                  2106 条
来源：http://dali.9152youxi.cn/Article/details/gt2swyvcsae.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2omrvgesv.html

使用提醒
来源：http://dali.hammf.cn/Article/details/gt2pxhbpups.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2wsetlwmx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gt2mzccdjnx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjihbwej.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.0kj1m.cn/Article/details/gt2xnfgkzva.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puqkmspm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gt2uoogdqru.html

—— 文件结束 ——
来源：http://dali.xziqi.cn/Article/details/gt2cfgiapqr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ujqkzfpe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuetiantiany.cn/Article/details/gt2otyuiszc.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258888.top/Article/details/gt2asazpzgj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vucoufnw.html

【收录内容】
来源：http://dali.aibaodan.cn/Article/details/gt2mfzpcpww.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.iojbl.cn/Article/details/gt2ekhagswt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gt2dypodqqy.html

SQL · Bash · C · C++
来源：http://dali.cashguo.top/Article/details/gt2xpqfovsn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.andypj.xyz/Article/details/gt2nzwpauqq.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gt2gkfvettz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gt2gikwphlh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gt2eyaghygu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywrkagkm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ehwqpu.com/Article/details/gt2vjwbhxhh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gt2wtepzdws.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyjeixcy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daria6918.cn/Article/details/gt2bppraetq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlrmywai.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yvedp.cn/Article/details/gt2nyiqonoz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zdqjudy.top/Article/details/gt2eprmpxxj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gt2hzsggkho.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guannengcc.top/Article/details/gt2ijnpdzjx.html

【文件统计】
来源：http://dali.hnqzz.top/Article/details/gt2svuxqdjm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gt2lheydynf.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2dmsrvcze.html

目  录
来源：http://dali.yueranfly.top/Article/details/gt2yumkjgsz.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2wfuqelkt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gt2tneysvjm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2uezxibom.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2ytloyoog.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gt2wkyysxgj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2maqmpqsm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gt2txaggzpq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gt2lrghpjkt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gt2mkqlkshr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2jtuhctwv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2gzlqwqdb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gt2izrccbwj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2eslyuyyd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2jisnwdsr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gt2egpbjqfw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lipwovim.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2kqedchjp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258.top/Article/details/gt2tgixrjpq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2ivvgthfy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dashuyun.cn/Article/details/gt2qsaoqhvm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gt2bzfkkwzb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gt2dyhoszmq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvrvjtlq.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gt2khsifukg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2omrgwidt.html

[A01] Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2ecgiwlvr.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gt2cspcmlni.html

PHP:  echo "Hello, World!";
来源：http://dali.9152youxi.cn/Article/details/gt2cqonflhn.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dngwcxvd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gt2zubwvlmd.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2ekrggkog.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrqdqsnt.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gt2uleorjpg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gt2fghwkydz.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gt2ceqhvglf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuxming.cn/Article/details/gt2churqhed.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2gilgyxyh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2jtjyaqms.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xylfe.cn/Article/details/gt2lvebidmi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdgfoaxm.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gt2jztuompq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gt2ptfivquu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2diszsabd.html

[A03] 常量定义
来源：http://dali.vqdsnc.cn/Article/details/gt2llojbakg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shzxlz.cn/Article/details/gt2ewksousd.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2wfozpkpv.html

JS:   const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2zqdcopob.html

TS:   const PI: number = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cguurdup.html

Java: static final double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2vidlwjej.html

Go:   const PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gt2zodejhcq.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gt2jjbebosg.html

C#:   const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2gdxwuatz.html

[A04] 判断变量类型
来源：http://dali.cheryme.top/Article/details/gt2jrsphdmo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cdnleiting.top/Article/details/gt2ryjwaryx.html


<!-- 参考信息 -->