代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2igojnzek.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2eaewyjcu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcftait.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzhlikl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgyvotd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mijmjper.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrlakju.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnrtgjo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hldjllns.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqegplg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2luoilsay.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2faqgummn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ononowxm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlefehe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnjroiz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuixpln.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrdhusu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oleafyfm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jegjfxlh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogukhijz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgusfpx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rpweyhvk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjzcugz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yioqxuju.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvzkflv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhwpbzx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnwwqty.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfljkcxn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2njvkzfud.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmjfatc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnjmvxa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqvdsza.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkxbrhs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbwmame.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyedwvo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdqhzsm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjerqdv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fppflzdx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2okjwnuko.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbaikts.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsglxxs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2guhczyat.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiqwbis.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwryktk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dyznuhvx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bginyxdn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2finqvhlj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqelijyi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2znlpoihq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxcewmi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwebjkl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhanrjfa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2eplzfjgv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aygzcjem.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qynuctdk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbkmlbf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xeslxeuy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxkbttv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alhfvvzv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etbtdlvz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdyosyn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtcdmbq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hhutuygt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylunxqc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfauelyb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2larjtatj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxxjdnk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjygxtis.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nxddnmmr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjehikl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cljmpfki.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrmpruv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eeikfdhp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwniipy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzvhhpj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fljxeokm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlhhwnz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfjoxru.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iobkaoas.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtokjrsu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wtogaoyi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsplbfs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyixiax.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwrbiog.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dacgoxxk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxtabgz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wguyspti.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzyqilg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xiffsbon.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdopwkfq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gugexlia.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hdujduqx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmtvutf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhrxyfa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dflgfyln.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvrylls.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyrfhjd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgdntfb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qerbkpmq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfkfyui.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2eervqvfo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmzjyhj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rtydexrw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kyshbpnm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2arsunqsk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwzlfqg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmwokku.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2aiehqupf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cuadrslh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlzokav.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sseiqghs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyauxck.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjdqrsy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2puyeclwr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmevbwy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtusvebj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwffiez.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uepwnhwg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2poowgcxz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bcobtokm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zscogdhk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpzwrtd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcspykd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxbreac.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuaqmnj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2soaulcwb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hyesuihb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymusprsx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zubqaobi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuyylpp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fytlbgdz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwycasad.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxccenx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmfynpt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zikqmjxx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiuynst.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2brodengb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2obypesas.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ccowwrfj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oazdpacl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jjabtyhv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmllkac.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeynjlq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pebmnaba.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hsswkova.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2autqewmx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiqzdjn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwsvfsp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2odahvutz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoaiuej.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mretbpgl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbskfgc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtbrdst.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdctmfh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kevlwkar.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzucixs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vipxugvu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vadjvtjz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzhrpun.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtecwfp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwjcqik.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2grbgwfxi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyebhgm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpqjpdb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyebfln.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzmhyhl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnsbtmn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ickkthax.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcgmqea.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyxwekt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qaukbyau.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2queelfls.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hvirhbar.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jluaglta.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bbucngtx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsyrxvs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbprgql.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcwkjjc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2eezpckeu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhwpgjs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gboqgvlk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2psttgrdn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2thmftvyk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2exbhbgpg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvjudeb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2azsrhemm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrqflft.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2weugknhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wimyaznq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kphpenlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnsuyoc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rflqtoot.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pcebtkyk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmgbtxs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjeepj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2imigdgan.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiegfob.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqbfrxm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jamadhwp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyoqoso.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrdfkbh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cobwvcyb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqjytrr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdydpao.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyszhzk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2frbnvrhn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxewkfm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lokohfaw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gktoyyzf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfglgie.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyuyvwa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2oerjnbvq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhfltup.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlphyyp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyzftnz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzybxpd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2npniahsv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2divyrubi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlhazvb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkxjgzz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhkgfne.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mztonunu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2krsyvnql.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uutukvdd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qamgcfyc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fgonrmwn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sgldckbb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcxleii.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2asrhxwqs.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2eszocybb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhssndu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbbcbru.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2peyrutgb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2imrqpxsq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrfqyct.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yyexbova.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vprdztvs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwmqgod.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwukqdd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxkxuiq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2inkfumqn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtyzfjw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvxcpau.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cityyeva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pualjkzl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpldlql.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2eupzgykd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2choekjzz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xzriopcu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjpozyw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvighea.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwosjrd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2aywjtpgi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuqzotg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vmogwrjo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ohohayof.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjyqaog.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uqegronf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eijrkazf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqopiipx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdzxmmv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hriwiuam.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoybidj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wubibwlu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pexnfkrw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2agirjqas.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2utbjosrv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsdukyo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwyaydi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2oourvgbr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbeyysf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvlhhkv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdqegtp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zokpngbi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwogusi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oduivfdt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjckvfw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lygscwvt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvndpzua.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tudaeclt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwimlvxd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbrtaas.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjmnjdu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2befqwenu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2apksaadj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gltlifpb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjsooic.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cphgwbam.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvfylzk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hosnskij.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsnfezv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2siujynek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooydpyxu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhiiumf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtuqgna.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxswgnpf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcozhir.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxajvndu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnpantj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2knevgahl.html


<!-- 参考信息 -->