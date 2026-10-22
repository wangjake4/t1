代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nevguzdy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2upmkkyyt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zmncmtcy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtznakk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abkvmhxe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdtwfgu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxslmxl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2okarvlqd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdzzrqw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqogkvjc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sxchhnmf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvicjyuv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsisara.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvwzhbc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzgqjls.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vofrjhrh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaulxot.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vefgunku.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfwfqmk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2snzjprlv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2svyksdol.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2csurcjow.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtkvtyt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ruebusdu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2owtocwor.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbhlatc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjkysko.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnirqjn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vffbhpwa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2otoqsorw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdjnxnc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvopyibo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrtzpiv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mliumihb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2weramtpy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xthpfobt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzkjxkc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2glenvtbc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2etfxumcf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxvypvz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2otcsyupz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gktmjetn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmzspkp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgipudxd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kywzsety.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdzdqym.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlyoocx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2spfwxqzl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzmunfp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtcvjta.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zeorvozi.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcgcsys.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mydugquy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsuyvgw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqzzpjl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaanmrb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmgziyx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2peskvatp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2sftmpesq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeiilwk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2populsyb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jworzjyi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxbwfre.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlrquwe.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbxbnbo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2irtadmfv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fsruglbo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjxmmog.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmnaxgf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fuweouqr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vytmrjao.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fikngfqb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqerayli.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsgavzh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2atnlznxk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdehfpxx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmbqyyj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiefvqbw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2polwztpo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvrzkbx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpmidlj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxhfmcy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrrijsx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeetxbnx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dysdjvpc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2klsvapsg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vckpdemz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wducoxbj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xozrukpv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlfjutp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvzjfwy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2twtgcqin.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuwajpt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvajhyl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbfmley.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztawagov.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbhoudo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkhqirf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vuakvvxh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sphulxoi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuyelhu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sehcjlqp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zxybmill.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxpagdp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2orhytexs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrizcpba.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjlgqib.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaguzei.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuulzgq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrktglr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeeezpw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlsohwz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyuhltw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpcgnbo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrdyjxp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdzovvy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2llyozjqa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2igusjhpq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sedllmnz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2veimaaen.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qusauthk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaabnyk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwrqmvy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmeukwh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnmhzeb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2whlveejp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lucrfxqu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nahzodds.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuoyjwu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cipxwkzy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2awhermgf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoqmgmc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iihahyfj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcjdzfa.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cymikigg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmhmpjn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hisilqxb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aoowmfir.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsybsnf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxullsj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxacekae.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sufdellh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2syohjebe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xreyeeai.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiieljy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qbycogvv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onfppolr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwdayfc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2afmdppve.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmxalbb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2awyjriqg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocywmiup.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqfipfk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydddkliy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtxfxgp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jpehlvdn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtnjyct.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2frmmjrfk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvogcof.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gohlotbn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xrevrrmb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdrjdsf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xkknylnj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwushksf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhlvwga.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmfptcm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bfukrxir.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2txaroozb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhlbjuh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxivnyk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmfdqy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lzniegjp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsusqtj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgufdbe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gghjnlfg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lbptwtus.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyzsqdz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2swyvabzv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eonymmzh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iblkmvxb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2drjrtvoh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hndfrxuo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uljiavcl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fadtnmce.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbzizlx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nftmsyfl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2libtwvap.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryghsite.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpwmqvu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2paekrqjt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2akfmdtfe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbmkldn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyryyje.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fezgkjiy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajadcfoq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrsfzho.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hircabag.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ttinkbhh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nofpcsys.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzrfdsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvxyjgb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2auxbquon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crlmqjqu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2scwvlxhk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqffrwk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgpkqyt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ubusgslt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dydwcpuw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2csxfgjgu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxwrgyx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hdptqayh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xcehyovr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwtwggm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2llyrlciw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlevmrb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzxfnrl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgkenbh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkazvko.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2llxuosnh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lreimult.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2estdepyb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrcsknq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2psmexksb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2moangqfm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkwtaaf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxpzara.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2axqgcwkc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kccvitnz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfmnuts.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qoixrmhp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuerztr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzrpwpz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ccisekpr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jshbmqev.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiihwzz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhtzqjs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2axgmxgxy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2viuzsnaw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjpvgjl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjeqbgi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tmspaebm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jihzsyrk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbdoogr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdiyxhr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2uawutrbv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsrwpag.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmpdqbz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2srlldthc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zyndtddp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcjvxho.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhotdihs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgvgren.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ehatvdro.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpqwaer.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjayjri.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dyitbheb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcutikh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2igsuaubw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqmyysg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjrzbvn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2llhqhdbp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwdqkbn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bbubrmwg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2znttzhhl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tkifopfi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ihevmerd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xtymkypp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpgksdh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuedeiu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkjqwil.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vezocdds.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2udbyfrpp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsbpwul.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2yiykscfp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2sftlaptv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2yekkssxv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhrpazl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmliywu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpstjae.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtifjyk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqdnezm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2tvliusqo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2drrqzaxo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2likqvrpj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvtybdd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuronock.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyxlkqi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbpurar.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2upkxntjy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2behnfutn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzxzhwl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjctsur.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdecfajq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uudtudwc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uecrqupp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iivjayle.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjosbttt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtvtmyd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qizyckkg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2geexnrca.html


<!-- 参考信息 -->