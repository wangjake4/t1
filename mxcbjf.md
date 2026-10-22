代发 wailian999

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkkuvel.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjovtsby.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2eakrluzq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvnkmdr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jukxjfqn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2roepigtj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaglgcv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2utrwjtdy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqfibli.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hswhjjmt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2crkuzkuc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsmmcei.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgaafte.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsadoqk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqonqwm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvlgffu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmkoemi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvruculw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2raqiqhrm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsyhsgs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dftulsjk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jakxguvw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jymsngus.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfjdkaa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rhithoxi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvracsj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtiekbl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fskkjxps.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hldczrug.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pftqbqmt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cevceftd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoicwczg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2njeeefnx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gatdfvfa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mcggpdjk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkllorl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxvjwoi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvphnblv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acajmjap.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2neyyvsyy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvdsata.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elwuwjwb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2alwxqizh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhwtqvh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnhxrx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tekfofbz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2knkdssge.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xykmvrkr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxzgywa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjnzipa.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbsiygk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjiuamg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2etgwzfbv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhavgmd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgvofzk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eznxwglz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2czyxkpkx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnmtujv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sipasvbu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrfdjxd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2luqpmenv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmitdoz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsjfkzl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cezwquoc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyseeeoh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsicwqo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsitfit.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoqjkbn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuvqyix.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qckaqcoz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ladryvyr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpqlkks.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaucurm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnrtuls.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dluaxzat.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2annaumds.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wygreldg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpezuhlp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eydpryla.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbcdwdp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzwkyil.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2crrstipb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2obszddjh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkbdbol.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2owghoksj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtgcegk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kspuonmb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrocbkf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfpdphk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owyqviji.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iasiyafz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkjjtxk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfrnhsa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pukabmje.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2knxantyz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcsbzgn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hntzsqnk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tluojctu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ryshlojo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiwfbdz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nbygjmfm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pciidmfv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfdiuwo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eflziqem.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2obfbmaia.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgfjjdh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2utvbylpw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhcnfkt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2npgbkzqn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ozawhxpd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcyacog.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vsleahkf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlhlaid.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2doahsiai.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnvtjyv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrmahao.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmnbqfp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjqtxsc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2izlhlyxs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmgwlpv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ixezwlwo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eomlmvsf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2woxufnew.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2llodpodd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrvarpw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqnwehu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrpbsf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevoryry.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2otqjmjyl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnuajws.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcbkoyf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpxgxwi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkkzvhl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pifdwcrl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdejsqe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2neakfqhv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfrogzq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvphgjn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujptotih.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtiipia.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuruqcf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rxamkjla.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2opnvuoxw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctggyjnk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcnpfmy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyltols.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrhndzm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrvivjs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfyntxw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymivdklv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqocnpo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kohohymn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iismdonj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmchybms.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoaiuoc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsslizde.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iqetwogq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2chkkrdrf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrunzpe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qraibgxf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqisipn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlrpieu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmatbtc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaukigc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2duzqgpfs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqfnqmf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvcrtpb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cvthoaqr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwxfthx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgzyebu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhpujdw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdmtvnn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rlslania.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oswpzmhl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuriklb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnffyrid.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwrvkte.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhojkrk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dskpqhgl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2worzhrgf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrpekig.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejurmdna.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lohefkoq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpskyvo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbjlhbk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zukucwba.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jatsltcd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mzopnagq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fadqknqa.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqbusyq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqomiiwx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bitxgcon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyxnzvk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdmbgvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yduqgypv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ecekalgz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2edohcnih.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oorpnlea.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcbdkkj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cwygmlwr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jzygugoo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpixucd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kgefpvdh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bstbssbw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ryenpdrk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdozvrc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lagmokmj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqwyfok.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcvogew.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdhbfpo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2optdeese.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2meuemdir.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2itkvrkrl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xivahswa.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvwvngr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgncjyh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sagdwims.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmljsif.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfzpect.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hinnpqja.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tidoabxx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkvrpqr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ggviyazg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pontttmx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pupoxcxn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxvhdbb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tnasmuhp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2orokgdzz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaqicsx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2najzyqaw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hyujelnt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvyngwf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pzejotjp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2loxdzbby.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgjvzsp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2znosatdt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ihygdffs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2euenullr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgdxcvy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2moeoekwz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnjfbeg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlwusyb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dsubcbyy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jwisdegp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rifnupuu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2reuftweq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfahmwgw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfaadfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stdylenw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjsdewk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjllbwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2noukqauq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyeprbf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2iniknnxk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iabguuir.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdnkeyo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwidtmfy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oienvflr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2koskocla.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fyntlebn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkbzxmm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsatfql.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfpmpfq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2emydqkqc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lykepzxv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuhfnas.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsocaer.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrkazty.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2blhaript.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eohqilec.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gohqzoxn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2binimdds.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qygeqcjv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbmpfqz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvewklo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhziohtr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrmnumh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbjkpfj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwkipwf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plthcjre.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dllqasfe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiqjbsu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfgsqxt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmvmsdw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxzmwyq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czzkiuci.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxrvuda.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mergiaej.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfjtycm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwhvwwx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzozxsl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twbzqlzr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyprjoa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjopfmvq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpakynsi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwpiasl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onswlafo.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhmijre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tklklpwj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twpajeio.html


<!-- 参考信息 -->