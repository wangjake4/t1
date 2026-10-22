代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gt2jtnjzgjm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangdashe.top/Article/details/gt2rqtdxoqb.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gt2dcxjcgyy.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gt2mpqcxgoq.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gt2hnkhzzxa.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gt2pkwfmvnk.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gt2bhdwazbp.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2xfqyofzm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhoulong.xyz/Article/details/gt2hzucetad.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangdashe.top/Article/details/gt2qhrsbddv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gt2uuztqblf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.bjfxy.top/Article/details/gt2xpkoterm.html

[U43] PHP：声明命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2hzmznerx.html

namespace App\Http;
来源：http://dali.cdnleiting.top/Article/details/gt2ufcksuce.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gt2bbbdpukd.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gt2iqwdpxyr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gt2znvjhxeq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwrwmqpe.html

[U46] PHP：可空类型
来源：http://dali.zhongyouzk.top/Article/details/gt2fiqndrnk.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gt2zgraedcu.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkabjiht.html

int|string $id
来源：http://dali.nwbrower.top/Article/details/gt2gwwabhpd.html

[U48] PHP：纯枚举
来源：http://dali.sxryk.cn/Article/details/gt2ckrrjntb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shuidangran.top/Article/details/gt2igxkdvuk.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gt2yaoyivif.html

public readonly string $name
来源：http://dali.jianghu66.top/Article/details/gt2sreiqcci.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocyflzcp.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czicdbyn.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gt2ixrpopex.html

[$a, $b] = $arr;
来源：http://dali.9152youxi.cn/Article/details/gt2jodtwcso.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2mzdzxqca.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gt2pbkcyavt.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gt2numwckov.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gt2rbeziija.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gt2thkpcpkm.html

$obj?->method()
来源：http://dali.iojbl.cn/Article/details/gt2irqwtfrq.html

[U55] PHP：match 表达式
来源：http://dali.yonumen.top/Article/details/gt2hivsgsxg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gt2grxunuer.html

[U56] PHP：命名参数
来源：http://dali.vqdsnc.cn/Article/details/gt2yickyujc.html

f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxpnlcmn.html

[U57] PHP：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2dgvkmhjm.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gt2aexrqowu.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gt2pefuckme.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2yddhmesz.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gt2eomgjtfr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2kgyahvrn.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gt2osxuoarr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangdashe.top/Article/details/gt2sirvehch.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gt2txelgwtv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2ertotfqr.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gt2wgyekkpj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gt2qvezpgqo.html

[U63] PHP：文件读写
来源：http://dali.birdmap.top/Article/details/gt2khdxtynx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aibaodan.cn/Article/details/gt2yslhndwe.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gt2fbebxunb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigufen.top/Article/details/gt2oaqrriks.html

[U65] PHP：会话
来源：http://dali.tian-w.cn/Article/details/gt2bogzbsut.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2hxnnoxke.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gt2iwtdnozm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nedxezkc.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gt2wddyrnoz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gt2whpddtjy.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gt2azuqqrad.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgfzy.top/Article/details/gt2fgkbqsfr.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gt2ldwsvjth.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigfzy.top/Article/details/gt2rxyptzcv.html

[U70] PHP：PDO 事务
来源：http://dali.shzxlz.cn/Article/details/gt2daloqlgf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gt2ldwuxfcv.html

[U71] PHP：抛出异常
来源：http://dali.guannengcc.top/Article/details/gt2gadqeshm.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gt2whjvoqqa.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2xnzowklh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gt2lurikixw.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2curbhjdx.html

parse_ini_file("config.ini", true)
来源：http://dali.xziqi.cn/Article/details/gt2cvgrlqnn.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2vdczvrof.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gt2lxpnagwy.html

[U75] PHP：依赖注入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2polkduwq.html

composer require psr/container
来源：http://dali.cheryme.top/Article/details/gt2vcexxide.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gt2kjpzckyg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guannengcc.top/Article/details/gt2yrqxscnv.html

[U77] PHP：模板渲染
来源：http://dali.tanke756.top/Article/details/gt2sncgmlat.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gt2eqqmwlgs.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gt2skqmqixb.html

composer require --dev phpunit/phpunit
来源：http://dali.chenjidiqi.icu/Article/details/gt2kviwyykq.html

[U79] PHP：静态分析
来源：http://dali.guowangkeji.top/Article/details/gt2izdhrnpk.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhyuapsn.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gt2qidbemgl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuanzhike.top/Article/details/gt2qualqbxp.html

[U81] JS：初始化项目
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uodsrikb.html

npm init -y;  npm i express
来源：http://dali.jinqigufen.top/Article/details/gt2cwfkyqlh.html

[U82] JS：package.json 脚本
来源：http://dali.zhoulong.xyz/Article/details/gt2hcayujrx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tanke756.top/Article/details/gt2lxbdnovu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rilcwpsy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gt2biidntuq.html

[U84] JS：CommonJS 写法
来源：http://dali.aizwys.cn/Article/details/gt2ogafzwyh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gt2ojglljdn.html

[U85] JS：可选链
来源：http://dali.gaohongyu789.top/Article/details/gt2ixfgxruc.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gt2ortjyxkq.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gt2ssfwodgz.html

a ?? b
来源：http://dali.zhixingplan.top/Article/details/gt2kdtzentv.html

[U87] JS：解构默认值
来源：http://dali.cashguo.top/Article/details/gt2dijlvmnk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fzhhl.top/Article/details/gt2eyewqyua.html

[U88] JS：对象展开合并
来源：http://dali.gaohongyu789.top/Article/details/gt2ezwpdfgg.html

{ ...a, ...b }
来源：http://dali.cucudq.cn/Article/details/gt2fgkbxwbv.html

[U89] JS：数组去重
来源：http://dali.jlsjyb.cn/Article/details/gt2fgclzwvx.html

[...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2ggfqbhme.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gt2qxilrbrm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2sqtygzxe.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gt2lkniipvx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gt2pzdpnngp.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gt2iemrnfbq.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2dkfegkif.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gt2ceykkpll.html

`共 ${n} 条`
来源：http://dali.yuxming.cn/Article/details/gt2nrkwdnlr.html

[U94] JS：箭头函数
来源：http://dali.yueranfly.top/Article/details/gt2zhdkgwvh.html

const double = x => x * 2;
来源：http://dali.hywenlv.cn/Article/details/gt2hdnzyain.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gt2gkpdcwjd.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrhgorrq.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gt2wpfaiame.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2rqfwpors.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gt2mfyquurv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2vezalzpv.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2txyqsmcb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gt2doepnmza.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gt2mmwnnqec.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbnbgsff.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gt2lhdoeepv.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gt2xtfejywl.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gt2xayhjkyf.html

el.classList.toggle("active")
来源：http://dali.xylfe.cn/Article/details/gt2rebfnkgx.html

[U102] JS：本地存储
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwajwqen.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gt2jhxgrioz.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gt2hpxctgwx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gt2khuaoard.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gt2yjqyitsr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2mtfediii.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gt2anleujgo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gt2vcsxzmlq.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gt2wchhmvvd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gt2pqcmbisz.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2btzxixqs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gt2dplbpgen.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gt2kckchyiq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gt2hiyyhaxp.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gt2wsdoyzvg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gt2dgyakxvb.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gt2xsxmyocq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehzyswzm.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gt2wkrrjdud.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2ftnjsswf.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gt2qxgnlkqq.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2exarxyqh.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gt2iyxofyha.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2mynikbpp.html

[U114] JS：JSON 深比较
来源：http://dali.yj202588.top/Article/details/gt2qgepcaqt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gt2aidfcctu.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2hgwxlibr.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2qyxrblmr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gt2xfygxaht.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfblmyqf.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gt2bhtiqzgo.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gt2qenxlypf.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gt2myyvtnxo.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gt2togvmqee.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gt2lkylzaqv.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gt2utuilgwy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obsdwweu.html

import.meta.env.VITE_API_URL
来源：http://dali.pycfn.com/Article/details/gt2buacgpjf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ekkqtqep.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywizbmhr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wyrhikfm.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gt2zddnvjwc.html

Python ......... 252
来源：http://dali.jqgufenzy.top/Article/details/gt2xlgxkcqr.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gt2jwvgtbde.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gt2cuudhtvr.html

TypeScript ..... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2iznhvsiv.html

Java ........... 212
来源：http://dali.gzhubu.top/Article/details/gt2arjsnrqa.html

Go ............. 212
来源：http://dali.hammf.cn/Article/details/gt2vmaretdq.html

Ruby ........... 212
来源：http://dali.cucudq.cn/Article/details/gt2tjcbxeul.html

C# ............. 212
来源：http://dali.pycfn.com/Article/details/gt2tiudkwru.html

C .............. 30
来源：http://dali.yongpay.top/Article/details/gt2zntbcgwb.html

C++ ............ 30
来源：http://dali.daxiang520.top/Article/details/gt2sthunfvu.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gt2pkocugmv.html

Bash ........... 80
来源：http://dali.sufxvd.cn/Article/details/gt2cspmmgue.html

Kotlin ......... 15
来源：http://dali.redwolf501.top/Article/details/gt2sngofidh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyzeied.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gt2mijejgus.html

Perl ........... 10
来源：http://dali.kuanghao11.cn/Article/details/gt2iykycmfg.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlkccpek.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2oubgdphs.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2lslbjwmx.html

按章节统计：
来源：http://dali.ivvv.top/Article/details/gt2btbqszet.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gt2aveipwzh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2txifwehq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gt2oormeydo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gt2iagdecpe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gt2bhevceog.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gt2nzelqeyv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejkrutbd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2ilzbrpty.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2sncwvbhj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gt2drbkqbkh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2fsaxvxxp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2utcdflds.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2fkjlcbgt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffzhdqyl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klzessib.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2tnrvnrde.html

Q SQL 专题                              90
来源：http://dali.shzxlz.cn/Article/details/gt2zoavgovo.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gt2phtwlosi.html

S C / C++ 专题                          60
来源：http://dali.meibo888.top/Article/details/gt2knukrsnk.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gt2tucwoxmn.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gt2xrbzzsac.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2coygpkrt.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjkbeafa.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2zmrieald.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwewavlt.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2bvlcclpc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xykfwmcl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.quarkkingdee.top/Article/details/gt2jexnbqyb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gt2vxqnltni.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gt2whgawbkm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gt2jzwwtbyy.html

—— 文件结束 ——
来源：http://dali.zhixingplan.top/Article/details/gt2bhpwphay.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yssbgwpu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gt2guohlwfc.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gt2okvrgcff.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ooaarxup.html

【收录内容】
来源：http://dali.ehwqpu.com/Article/details/gt2iyitywxy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhoulong.xyz/Article/details/gt2yhdftdri.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gt2boyzpgnf.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gt2dgofkqjj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gt2ygvlymfl.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gt2byfiwvsu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxoabuxg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gt2avogzeji.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhixingplan.top/Article/details/gt2pgeifgmr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.meibo888.top/Article/details/gt2xphlsdgs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gt2vezdtauc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gt2bjxiiete.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guannengcc.top/Article/details/gt2vokmgqoe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.snrcjt.cn/Article/details/gt2ovongumm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jlsjyb.cn/Article/details/gt2vzdxcqtz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aibaodan.cn/Article/details/gt2loeuiriw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gt2qdwapwla.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sufxvd.cn/Article/details/gt2tcsvkvfl.html

【文件统计】
来源：http://dali.zhixingplan.top/Article/details/gt2bsojdxup.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gt2ctuhnqmz.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffrrcdrx.html

目  录
来源：http://dali.hnqzz.top/Article/details/gt2lddhlxkn.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2zjfzxvws.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2siuvfovo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2ahcazocg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gt2zufcxkvb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenzaomai.com/Article/details/gt2kckpqctn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hysaishi.cn/Article/details/gt2uugnytsf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukdczwbd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gt2iawqptji.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gt2ugibblta.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2jfciwtuc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gt2clvycxpx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2ezvmelzc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2ifzdxseq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkqedsmj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2xbrnjtri.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.iojbl.cn/Article/details/gt2itmwylnt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2qtiacptk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2eirdfbza.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gotoacloud.top/Article/details/gt2fjpfbvfh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pycfn.com/Article/details/gt2xcyyndsp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gt2mtooxrmd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdcbgkqs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jjqtfbeq.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gt2ivwpeanb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2pqeidyhl.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gt2osodlfxr.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2mvsvrfdy.html

PHP:  echo "Hello, World!";
来源：http://dali.aizwys.cn/Article/details/gt2hhhzgjpx.html

JS:   console.log("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gt2hewihytp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenzaomai.com/Article/details/gt2nexodhoq.html

Java: System.out.println("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gt2ubbyqcvi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gt2txlxvbnf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bizeonpx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gt2dwwyurah.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gt2gaquoqqm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gt2aygkwcvi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2rdtsqscj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2qvymyahj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.316326.xyz/Article/details/gt2xmuiyije.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2mubotbss.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gt2cflgssiy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangdashe.top/Article/details/gt2hyioacqd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2knzkuvlh.html

[A03] 常量定义
来源：http://dali.xylfe.cn/Article/details/gt2youwxzrj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ivvv.top/Article/details/gt2acibidrj.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2eyhxccxm.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2rtgkjxsw.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2drsuhxie.html

Java: static final double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2frxjetzl.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gt2qcsmpkdp.html


<!-- 参考信息 -->