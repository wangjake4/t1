代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdendbj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppznsutu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlgruta.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2prudtrwy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfxxoxz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zobqlwkt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbarcmi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mppeawdd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdigepm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2swlvgurg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kasshcto.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2luanwtsv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnqqudg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfshhjpb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrhulix.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnaaqfw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhspbuz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2psnpgqqe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2heqinbbf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnoiqma.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwxxcue.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhdooet.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nshfwkvd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2stfxacse.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjmdaiq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlsxnfg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qiowfrzh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmvrqok.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smydhchf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2acyhfbwn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2llmpotau.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgavikm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qknwvzxl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vfllgtsh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmkkmfw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luolenes.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2svakubqr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhnvzez.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnikmdn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuuehei.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2inryjgqa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlimjinw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaflfhn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkksgday.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxfbrom.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdvqxtl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfbrfja.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqgyajt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2metdtupj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpnamjt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmpquag.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwspfoc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmevles.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjwtsgu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kmruitcu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2usidkhzi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmbfida.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wafuzrah.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cagllpat.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjcsawy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sbazobwf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cppazlfd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2agdnscas.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tplgqwty.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sykcxshq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abptgept.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbfyzgs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uywhhmlf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxvilin.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnxzkwc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqumkxod.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdpxnld.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfigzsr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2amyopmvc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcaaibp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2atawnlwz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxbfazb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2byqxnlui.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2etthargw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wixtudeo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2niifzjxf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kshyzppc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yagupfzi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2duxblejn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xuotxtue.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2japbmkjj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zyupevrf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxbhmzv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2znlfieyo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbzaxed.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmdrlgp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ofckhnev.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaosske.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xauutltd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvxcgtj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwmlmec.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfhggep.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gegnuzau.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yyofvhxw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tipozehw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kesypqkn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiytqeb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbagrki.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcimkik.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2attkdlmn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2beuborjv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeyarnj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzbjrvv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vafdhlfy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsahrzl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbearge.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dssgdosq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lablxhom.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvexcpoz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgwvobe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2owprlchj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrkxqjv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vwidmgbi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnmupwy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmpebph.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqakras.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxbpzap.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpttonw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzckqir.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzluzer.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2acndrnvz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzdjwkc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gixbmdwa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcgcvwu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvihfqfo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2minxndnn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pltkekqi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qugqcyup.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfhjdys.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmaqjpw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwxtjaq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnkyztg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwlcfyi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hznsaukf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkcuexl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2okkuqzjk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdwxnob.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnmqbig.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrglveib.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvgaxbl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hudhqeqy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbpncow.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvobihe.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ronmlfhn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfjnifz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqgzsqh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2omjnncyj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2utmnuvyu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2azjqaexa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hfecllha.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpvhfgr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyqvmjr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lplfmcmi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqvvcba.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsfscva.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfordqd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kapydyni.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlmggit.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmxeovx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2spyhpttb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxcufsp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmrflnn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfpppgl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kelatstb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaurrwj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvgwhtn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcqbevb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuxqkxs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2esrzxfig.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbgnnxz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlzhsje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otestevd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2luhahemy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klztdpij.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzzrohv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzohigv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2inpcaexs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbaymim.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcchnbf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2swtjntmo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkezcwt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zojefduv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2olnvvmnm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2apjgkvwd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tlljubnd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wksgqffl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxqywzr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxasvbx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyvhucz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxohucd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrrovbu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrpazay.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmzwqtv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eckxxmal.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rillxssb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxnlhpn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzxkklk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dsebzhly.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdlbniy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2daaqpnom.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcnbnso.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zwptnbgs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqsuhp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bvogvqlx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aoigsimj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoeyzsr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvagtmd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2shzionjv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nigsadvt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2grqcnhkb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbshfiu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrfyhyk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpqcrrx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyggctl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrvrpmi.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2uupkzgdh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qeddpkxf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiihukh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuwbqik.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhvvxps.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cttxpazr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fhughcwc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaskpov.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpnooyl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhypsfs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bmifbaqy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnwmyai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irhwcxvv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fryqnqxi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtfpeok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npxsvzij.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2illvyjlc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvjjqos.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2htzxvlqt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kkalwfac.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvpxhht.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2drwcvkra.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrrbbdu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkujdae.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2eenrkzin.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyxhuud.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nueczjgb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpabhkr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2feysycva.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrpksdx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzfmbfk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hbioyuwu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkpszbk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2denrdndo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2auuiqcsf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyohstv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzyqupg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pbktgxbp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfduvxbl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfzdtsj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqdwrjz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmeawag.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsjqwqj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyaadru.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yezwkyia.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybljprti.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzwlpea.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbqkfgh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gavlxjyi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqpibmi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prouqxxm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlozljui.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aradjjyt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvgxjqs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jadprbzw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxrwysb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dalpnnui.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdsvctx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyduqqmb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcrcfmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcporfiu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjqmoha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eetyzsla.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmlullt.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzmeggm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qanhnutx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kryjvrrh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsfvgru.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqzyzgo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqnoaya.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyczptd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnssuhmb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmjidhv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2otorswzg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoihrqb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vozgizyn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uscowqzi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2riqlhcpw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2epvlxlxy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2smqqcdtg.html


<!-- 参考信息 -->