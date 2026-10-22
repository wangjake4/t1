代发 wailian999

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zelmcncc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbjlzvk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yofskruw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjzekcb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ukasjgvr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mikdjhsx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yacsysdl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2psilkktr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcooqkz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcrehpf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvhivga.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvodqmzu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkbqvrk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oegsvtum.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nwghxnmm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hqztbwzn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnmdvbv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mehwxpqn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ycllcgrd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpqkwou.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rebplveu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwphgbt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2skxirbxf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2whepsnym.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wozswnno.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2npihxybx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mcroohvv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bprwqnht.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaywisl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qomcsgcr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pymeadxs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azwkbmys.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kffoabyr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2chqcgsge.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rlusuwym.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbifbeh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2svnhebbs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2casqdgsp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vprflqga.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjnwnom.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdbolol.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfxwgwd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tortjkwe.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvivggs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsayciw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xdusnale.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzxojyg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvvgyya.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oohqgzkp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwvkzus.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bdochubh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orlfqejx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gelobdaf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbkvyqu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ritecuqz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2neegsofj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiovnlo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wefophay.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaifcgd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2auffbxvo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2crxwitsn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2thjydfwb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlveaes.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoovdtmq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcllcer.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nllmoafp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lenacrqo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnrffyi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjepfhpg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsvejaj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwdfwnw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtooqcuw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2whdfatld.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzhmbzs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfwmrey.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkmbpdb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2egqekume.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2csmexmzh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxhiicw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbyfuzg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2offhixfj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2etmmfebc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzmcddp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnjdzgn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eakthuzp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tikiesgm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcuzmsr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nootnrtc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2etgjqebc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyvrjtm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbvfpiw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2enabvtyl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iuilmtuf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeekcna.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rwffyatm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2acqvcwpy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlecjta.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhitsqe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sayidzgt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhrufik.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsuknbm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xltrgxjk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnjkhjh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzobzuz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fiznzjjg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrlbpru.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bekbalkg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kehitztq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kifwskgt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2srtyohef.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vgturykr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpquqvj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hifbajvv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlbkunf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2amajznbr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2webhdvip.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rteyicye.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmvpdbc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2deomcnbt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxcpecx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ooicbcha.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ryidtpnr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrgxui.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2brfbowua.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnnlerj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bocymksr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hweewels.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdvghwo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2blcqaomd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfncxhls.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgrbncq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbgzifc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxgmkay.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzcbujf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdlcydm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbesmers.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvhnom.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2acqtyzap.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsabjyj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkmulbw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtbfmuw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdxbxrg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuheifg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udjusesw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tehlpcny.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjatapx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqreetv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdnioat.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yebllvul.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwetpac.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwourju.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogppnvcy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvoaksm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eozqyovk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcqiziw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyghjhc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpkapdp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhopzpl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2urtoinok.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2shqaxeaw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmsudoy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkttnvuz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnazokrp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2awrtpotx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zrorcmcw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqwefjw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2quikkfsa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fdawpiko.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvrbdro.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmacxegc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpnwxbt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zypbsiky.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfzrcap.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyivpbp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoklyem.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqvubtt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpzvsbl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiegaxv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkbmqnf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnujjwxb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hykemtop.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2stkoomej.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrbpcwz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvepamk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uwofyhfy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zcytojcu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjxbbde.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzgrvsx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2albcceav.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nejajjih.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2peshtcvl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmazrpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzyapeh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2empfknie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfclatvi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfolsgj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uiavjcek.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rymweaqs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2exdhagbq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlseqee.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxrqtnu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyfaqas.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfkndyy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ysagcokp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwqgerz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xkydjxbv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wxthhuiu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbftyvm.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tttlhfbd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnfjsex.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hxondyyp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fhylmbar.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxvgcsd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjxcfyh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wqolvqrp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fryhgymj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuixbwr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvcrbqs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2srjmuihl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2biashtac.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cgradvas.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sidptiiy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxbyckb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wnorwbej.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiijjso.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2onlfnkph.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eypvsljv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhhfoza.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rdomrawh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2apxybwcq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgcgiis.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pccciyvl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzhihux.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqagjeb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nogwrkrq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bnunvsfs.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzrebfp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wilyidru.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2djhpyqoy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkulinr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hepujolo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btjfoppi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmupgcu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ryplzmxb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xiofnzpo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ongyonla.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrdzzvf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaelmtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnzryma.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlilvsdz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lztogkma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uryjplsq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2adxirxzo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpjlkwn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgjvmbv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbsrzng.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zogycunl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2abbykvhi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ustxpaso.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xeawpsvq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2logfasns.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ehddfxur.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyydtmp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2sifaqwbx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ooovyipb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nntxiwyg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2axveeoar.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jblybrle.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2omrcbpih.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbyjefg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lprujtna.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoiqmfv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ecitldmi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zymaxjdc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpybhkg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plucchby.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuogots.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhzfatm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drtgjylj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lalbnafu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqohcxvj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alcuwsgj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzsdauh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sboymvwn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbddqxs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwvaevt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xasnogit.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzxfdiu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaskonc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdjldik.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2afxsfxld.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlavgbzb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoewpms.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otvcmeeq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qegfzhaa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2niantmuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmlwlrf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2glyooofo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2titlfyuu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiuvhyn.html


<!-- 参考信息 -->