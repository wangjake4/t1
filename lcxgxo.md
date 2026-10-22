代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gt2rxgbifxy.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gt2uzlungir.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gt2sgplkvib.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gt2iwetikfk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gt2nsxdtxus.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gt2rcwzjrsc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cqqwz.cn/Article/details/gt2gnzmtnsb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gt2vbkgwksl.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gt2vhmxbscu.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gt2furazwkz.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gt2pbqdxafh.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2gjtwprbr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aizwys.cn/Article/details/gt2eyjhzppl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2vgjtfdgv.html

[U46] PHP：可空类型
来源：http://dali.daxiang520.top/Article/details/gt2givvcxyf.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gt2reuymvec.html

[U47] PHP：联合类型
来源：http://dali.shzxlz.cn/Article/details/gt2dtqxqxia.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gt2pzcjkhqg.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gt2rogwhcmm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gt2eupzfyui.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2plqmphth.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gt2rxaeaoop.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gt2chzehrdk.html

public function __construct(private int $id) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buzjvnya.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gt2mmbajobv.html

[$a, $b] = $arr;
来源：http://dali.zhiwuduotai.top/Article/details/gt2frwlnmkq.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gt2djvjrlps.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2cfbbqjko.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gt2msifhpvk.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptirovcf.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gt2vrscjlta.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gt2oxvnfeku.html

[U55] PHP：match 表达式
来源：http://dali.daria6918.cn/Article/details/gt2wgmbyixb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sysykeji.top/Article/details/gt2ibzhwfdj.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gt2egvtopba.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2vjimvbsy.html

[U57] PHP：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2gncxqegd.html

"值: {$a}"
来源：http://dali.hnqzz.top/Article/details/gt2vogqsilv.html

[U58] PHP：数组三件套
来源：http://dali.yj20258.top/Article/details/gt2tnuwlhqy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2qegglgyw.html

[U59] PHP：自定义排序
来源：http://dali.gotoacloud.top/Article/details/gt2fiyywane.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2scaumgdy.html

[U60] PHP：JSON 编解码
来源：http://dali.cheryme.top/Article/details/gt2nyrwikvr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenlongwang.top/Article/details/gt2exkffljc.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gt2cjyvzunt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2eaibuoxm.html

[U62] PHP：日期对象
来源：http://dali.meibo888.top/Article/details/gt2mgpmkndn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gt2odyamcmq.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gt2rffqcidf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gt2wwlseoof.html

[U64] PHP：目录遍历
来源：http://dali.birdmap.top/Article/details/gt2lwwkinjh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hysaishi.cn/Article/details/gt2refudexu.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gt2ctsndixj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlphwcwi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhengqikj.top/Article/details/gt2lmtgcbmo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gt2ljfnyetz.html

[U67] PHP：处理文件上传
来源：http://dali.cashguo.top/Article/details/gt2qgyftald.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zogvlsue.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gt2hloyiftd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhoulong.xyz/Article/details/gt2ijvlebsj.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gt2eypllsvl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnmnqwuv.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gt2ttpcpjaq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xppxddav.html

[U71] PHP：抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgldfits.html

throw new RuntimeException("失败", 500);
来源：http://dali.xylfe.cn/Article/details/gt2kqznimsc.html

[U72] PHP：写错误日志
来源：http://dali.gotoacloud.top/Article/details/gt2enjuiltp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangdashe.top/Article/details/gt2sjkaofhk.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gt2irzvdpsm.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gt2hkkiuned.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2krruhkyn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgufenzy.top/Article/details/gt2roxxzame.html

[U75] PHP：依赖注入
来源：http://dali.xuanzx.com/Article/details/gt2urzrcilk.html

composer require psr/container
来源：http://dali.nanxinkj.top/Article/details/gt2tcrogwlc.html

[U76] PHP：简单路由
来源：http://dali.jiagoushi.top/Article/details/gt2loefbqtr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gt2mfchelgq.html

[U77] PHP：模板渲染
来源：http://dali.chenlongwang.top/Article/details/gt2cvnaneyh.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gt2ngfmmjlu.html

[U78] PHP：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmqgpzkg.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgufenzy.top/Article/details/gt2vsgnxlrv.html

[U79] PHP：静态分析
来源：http://dali.nwbrower.top/Article/details/gt2oegyxmvc.html

composer require --dev phpstan/phpstan
来源：http://dali.dashuyun.cn/Article/details/gt2xgatpmgy.html

[U80] PHP：代码规范修复
来源：http://dali.ppjwa.cn/Article/details/gt2bvumjlqy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gt2rheesrvr.html

[U81] JS：初始化项目
来源：http://dali.birdmap.top/Article/details/gt2ukyjchjp.html

npm init -y;  npm i express
来源：http://dali.chenlongwang.top/Article/details/gt2orwmeyec.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gt2qrpasgch.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlgzpnqb.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gt2igodlpxl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ivvv.top/Article/details/gt2szsjimbp.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gt2jwdfxrow.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gt2manwcheo.html

[U85] JS：可选链
来源：http://dali.daxiang520.top/Article/details/gt2bbosfhbf.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gt2bclyeliw.html

[U86] JS：空值合并
来源：http://dali.nwbrower.top/Article/details/gt2ahmxvnec.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gt2gnbvlysr.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gt2yvlnnfdq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.c1oappe.top/Article/details/gt2fkkuvrlp.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gt2mcaiocbk.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gt2iuegqfnz.html

[U89] JS：数组去重
来源：http://dali.zhengqikj.top/Article/details/gt2etbovcau.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2duvnzxts.html

[U90] JS：数字数组排序
来源：http://dali.nwbrower.top/Article/details/gt2tdyjjspv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2hrewxlge.html

[U91] JS：对象键值遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2shvunjzq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gt2yvpuohfe.html

[U92] JS：深拷贝
来源：http://dali.xziqi.cn/Article/details/gt2qawhpgoe.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2golxrzkm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bztkwyei.html

`共 ${n} 条`
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfhxeyhj.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gt2zaybbynt.html

const double = x => x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2bjwqmfoo.html

[U95] JS：Promise 包装
来源：http://dali.yj20258.top/Article/details/gt2sdkegjdk.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgufenzy.top/Article/details/gt2sdnjgqiq.html

[U96] JS：async/await 与异常
来源：http://dali.ppjwa.cn/Article/details/gt2ardifcby.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2zthctnnf.html

[U97] JS：并发请求
来源：http://dali.ppjwa.cn/Article/details/gt2ckhiaavm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2rabhkoqn.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2ixhaoeat.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gt2adgsfnxn.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gt2uwtczyqz.html

el.addEventListener("click", e => {})
来源：http://dali.hysaishi.cn/Article/details/gt2oyzkyebt.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gt2lbdsspyh.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yherppgj.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mclvlkij.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gt2qpkwsrop.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gt2lqxblqga.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gt2iowmaanj.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gt2yewdpbed.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dianchejie.cn/Article/details/gt2lhfqthqa.html

[U104] JS：防抖
来源：http://dali.wangdashe.top/Article/details/gt2zxxyirvv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2zsaleggb.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gt2vhlgfvrg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daria6918.cn/Article/details/gt2pxnrymmj.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2dufrpbsb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gt2ltlvagui.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2txjourhc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2wybujgwx.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gt2aavurben.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gt2vyysyxsm.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gt2pwtsdlwb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2nkusxlom.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gt2hrxapvbv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gt2yztcgfmg.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2drozfcxt.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2idfjtyvh.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gt2oaihxxld.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2vgytjwnh.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gt2tbdxwtoa.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2ximltayv.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gt2abmidfzi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gt2jxpxojpx.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2wabbeskz.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2owtfaodv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gt2djhravke.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gykklyim.html

[U117] JS：单元测试
来源：http://dali.xziqi.cn/Article/details/gt2rhgkfzfu.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gt2hxtilnqn.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gt2hcqibvob.html

npm i -D vite;  npx vite
来源：http://dali.9152youxi.cn/Article/details/gt2qoslgict.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gt2fwezitqa.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcnnijmd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuanzhike.top/Article/details/gt2uasxourp.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gt2kgzdzxrg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpchfdcr.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gt2hjgbozha.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vvmbkjjh.html

按语言统计（条）：
来源：http://dali.yongpay.top/Article/details/gt2znlpgcbf.html

Python ......... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2xdxkhwrw.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gt2qinejpzs.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gt2lxphtdsc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mysbworv.html

Java ........... 212
来源：http://dali.redwolf501.top/Article/details/gt2wzanmqqu.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gt2jfiqjkxk.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqlrwnbs.html

C# ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gt2rhxzldwe.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gt2loyifhnn.html

C++ ............ 30
来源：http://dali.zhixingplan.top/Article/details/gt2mlyhkblr.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gt2foqmahbk.html

Bash ........... 80
来源：http://dali.hfpthk.cn/Article/details/gt2qtjsocah.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gt2xscocyud.html

Swift .......... 15
来源：http://dali.fzhhl.top/Article/details/gt2dywggvgc.html

Lua ............ 10
来源：http://dali.yvedp.cn/Article/details/gt2gfxqvjvl.html

Perl ........... 10
来源：http://dali.0kj1m.cn/Article/details/gt2utumsvqh.html

Scala .......... 10
来源：http://dali.bjfxy.top/Article/details/gt2csuvduab.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2ftvfcdes.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gt2dbrrbcjo.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gt2anfmssqm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijcxdhqh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gt2jpszifoq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2aornhffh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gt2nsyupwos.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gt2mmrrwznp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gt2uyoanpdl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gt2zpzuulfh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2igkxyrer.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2ymlykjbo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2xpdybrkv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2vvwhcmbr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gt2qklznbwk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2hvpdthfb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gt2cqzkuqpn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zycfv.cn/Article/details/gt2fcjfjmnf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2tsfntkmc.html

Q SQL 专题                              90
来源：http://dali.ehwqpu.com/Article/details/gt2jimztgzj.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gt2iyrtjxyc.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gt2hglezzcd.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gt2lyjywevl.html

U 高频实用片段                         120
来源：http://dali.hysaishi.cn/Article/details/gt2xmaesqhy.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2ypzqaexb.html

合计                                  2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2oaaistcd.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2drnjiful.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gt2ksllihno.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2qstvgbmc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gt2bhinaekk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gt2lshyvlvj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxuanxn.top/Article/details/gt2zgqnvgpl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfbufbws.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gt2ngfugfpu.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gt2otnkqgen.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tyryifop.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gt2mughrbnm.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258888.top/Article/details/gt2whafnwxr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2gglidrqq.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqpqoptx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gt2tjlspdvy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gt2hjgtzspo.html

SQL · Bash · C · C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbfmhrmj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.snrcjt.cn/Article/details/gt2zrsmqbim.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suszwcqz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gt2zsjuwrcu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.kuanghao11.cn/Article/details/gt2wfhnljbt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwxijslm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gt2icgrgehf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxohmdgu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gt2yhiyazub.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sufxvd.cn/Article/details/gt2ewqldkve.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.vqdsnc.cn/Article/details/gt2unxzgfpl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gt2ozfzuxns.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hywenlv.cn/Article/details/gt2uhhplsax.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkvegtlf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gt2nvwezoag.html

【文件统计】
来源：http://dali.zhoulong.xyz/Article/details/gt2azcqllqu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gt2vyjtgopd.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gt2bzcdeuoi.html

目  录
来源：http://dali.jlsjyb.cn/Article/details/gt2ababaexx.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2znlidnip.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gt2gwcjmyyp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gt2pipbpbnc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gt2rbgvjbzg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gt2akmsvjih.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsmfdkpp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2utryodsf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gt2emjnlcit.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gt2uchlzcgu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osuvcapc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gt2auvgqpam.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2agbwwukl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2nyapyeqq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2zhhuhrlj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gt2pbvsznwn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cashguo.top/Article/details/gt2brlrbmzd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2khkefcsb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gt2lkbzfvyj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2comyvxde.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2vrobglzd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gt2mpvlheyj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gt2jyhhwbkp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rxrmpain.html

A. 基础语法与类型
来源：http://dali.tian-w.cn/Article/details/gt2lfrqcgfv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2rhjlqdin.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gt2jajmsekp.html

Py:   print("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gt2whaqndbm.html

PHP:  echo "Hello, World!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycjaikjy.html

JS:   console.log("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gt2fqhzouvt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shzxlz.cn/Article/details/gt2iqwcsamm.html

Java: System.out.println("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gt2vsehioea.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gt2zbcjusyt.html

Ruby: puts "Hello, World!"
来源：http://dali.sysykeji.top/Article/details/gt2koeuwyen.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gt2anxacdyo.html

[A02] 变量声明与赋值
来源：http://dali.shuidangran.top/Article/details/gt2wnsixuso.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zdqjudy.top/Article/details/gt2kixapowf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yvedp.cn/Article/details/gt2aiygprpb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sweek.top/Article/details/gt2gvsqvhnd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj202588.top/Article/details/gt2gruesckp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gt2ymwevjdk.html

Go:   name := "Alex"; age := 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teprgldu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gt2fkzzauls.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjrmdnkf.html

[A03] 常量定义
来源：http://dali.yuxming.cn/Article/details/gt2ipcicsma.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttxawytz.html

PHP:  const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2knvagxdo.html

JS:   const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2vnexmoae.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2adpbtkvd.html

Java: static final double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2oevdyrfx.html

Go:   const PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gt2wpsajjyy.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gt2ufkrdhsh.html

C#:   const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2bbrypzmh.html

[A04] 判断变量类型
来源：http://dali.zdqjudy.top/Article/details/gt2xentdfiv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gt2sfjparus.html


<!-- 参考信息 -->