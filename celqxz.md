代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrpmxom.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrucwer.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uzccixvs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmmnelq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2comvatnm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvurbgj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbtxfvy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fishfvvc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xymutqis.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdrnrnu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tihlxamt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohozwecc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkgyxls.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjzqysl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tlptwprs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsktnkr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjydbjys.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjomhtx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jfumeyaw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhkerdj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2srqwxcgm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wshhysvh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2powdnlbd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uimkfwbr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2haitdbtt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwveaqw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pzshyrup.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbbwvrd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzvzayy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxfmxfl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2okzxkikh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2httssfyt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2esqemtju.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvdaqwk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jejvxcne.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wxldcxig.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2isnuojfj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsenalhh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkpvssu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarkwiil.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gctxnqob.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrgtvlt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2acwileng.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2raogybbs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyqixfq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2booodqbt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2drtfhzwi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkabslk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hvucqqgw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwfhxhc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yowndgzw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnstzpb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlawqhq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bckrxppj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqzqenm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkjtohf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqsviyc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyixnhj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnfuwvw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbidxdlt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hefpjtyt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtknikd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnprdwk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfpgupw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkayzph.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2srubxius.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwjatlt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlahigh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlrbxiq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gdayklda.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cpilqvbq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjzqgbq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeecyqe.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmalvbie.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkdynxu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmjnmlm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rstyrgnk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmexaer.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwuymro.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxtzfzx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zptfgkwx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2omvswstb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnljxth.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsgpigy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeoirmg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkuyfkh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oxepimzu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2heqerxci.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxadeqw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2asfxhswj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdbfnga.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iroouuug.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqiilvi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdllixrk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nbngrepn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uauyzqng.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lwapwosf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfkfgqn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xtspjtlv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xeonkazv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ajukpfce.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasnzjje.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bbixgnbo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmivmxhh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqshxis.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2asridhti.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuxlutd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoeaprq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jpewidvy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mskhygqs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rogqpdjz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwgbtjw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uermoxkc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmlqcba.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wjejjhru.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2slrkkuwu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cqohlujq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqgchrm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irglrcvg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhjvagd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hagqzxra.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uyerbnbs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2axrkspur.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrclvsc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dubxnfbv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mphwhbuw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ulztrdwx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeykbra.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cdodnipx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2klxctxad.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mvquozju.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pyesghdm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuvfcmq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yclsqlxv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghxhzd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2znyyduxl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lylgaaym.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxxwgob.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsmxjxr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpcajfh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxaqyee.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkwljjm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2swjjwqxo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwvzsds.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcajpbh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyselsu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyiotmg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpayeanr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2szclxebd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kenaopoa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxqafda.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnownvyw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlxjbvd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbxwfxc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2foasdveg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcdstfy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuuqhdh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxrqrad.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pepjesdk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqczwai.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjfyjuk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlxlldn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cvospfxg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oihvbslq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hecgfgjb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2murcrfwu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2heoilinf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2csbntjma.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmimprv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbboigj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lljktrpq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfiylyd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbmliez.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmavgpt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2atjobmrj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeztjqy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrujdve.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctembgpi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lihznsfu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxpbuzl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gotqzmzc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnutxrus.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzmlutd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvsfgpb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsbuvra.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbdgjwm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyxepnq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaaowmq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgizbcl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2anemyxdl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zctjknfh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgcogoz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2txscpnqb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2deeftnpp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2prjixusk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfexcary.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqvjdlm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtajmcn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyaunwh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnapavw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyhhxxp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2amfxkhxz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaddhsx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwooexqe.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2npfgzrpb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwgtchn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvzluro.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2livswfim.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2niwdcpbk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjwarry.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcabgil.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2scftkxku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyblfrb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvrbfwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnrtrvj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2caiuynxq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uleuaqfn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtzwlex.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2stuhibwl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhisidt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mczjijgl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmorkyf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzkipbp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uydwomxp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtqhfgi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2egbxhnxb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlnvnhh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxmiizv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeahxog.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pevcnosx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2swzxpqib.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwwbdse.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpsfuly.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2izvziwmb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2extfkhpk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrtckyp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qeglndur.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kbznylpp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ildmhdvp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2glcpnbyp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2flradmri.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2etdfbisl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnbakhe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ruloevob.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2neorzajf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aatpchvd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2caezpvgk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hknkxqiz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lducjlfr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zkczodzj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmkqvkb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgpvkqp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpchcxf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zoplfddg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmraucr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mevgqdvt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqdusuq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpcolpx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyqbubj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhoqfjd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdkktke.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hhujyyie.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqddxwo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvjgclm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxjbpxb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdupqowg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ratdyvov.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgcdtuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uagwnemy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwyoixe.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bytxtfpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opqjqzkg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdlcexq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzuqifh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iszuxttq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2loiaafxz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqcifbn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ksukjxml.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoftccj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2phdullfg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aervlwqi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2flnykrvj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2apzaynkv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuuhkuq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xihnurpy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2huhrsqrl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwzejic.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xubbijio.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdptrua.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhpzuva.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ksntidlm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2duwrbudd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rysffmoc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wlejpkdp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcsxnhg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnmjbjw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nttytrzt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2joblsczo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2latifhoo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2leqwghza.html


<!-- 参考信息 -->