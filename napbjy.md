代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eeprrhpj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugttajgu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdudavsl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2spugrqfu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yamjghzj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yijrbkcl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nemphufd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjogqkbk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kiglvgsu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerfmmft.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgwtsqn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfqfgyy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcdmqsn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2prlslkkd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qywlautf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylsfyjd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkpigjm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2onyacijt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cesrmczc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjajqnb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmjjgmo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkxjdud.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fpylikni.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwgbtnt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eusrvokn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxbofnl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2siarzzib.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaptodq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpivcra.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cebpwckp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2povdzwle.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2swqkwicw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmfgehe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wrawqxkw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqgoofp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdtctpe.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iuntguey.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2idxgrpas.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxesqjv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlxykjn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2guvhbzyo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lntclmsc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fizsorvw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiykcls.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dytojsrq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2guijsujx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrlmbvi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2drkygwxe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eegcrcdm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgoidkh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrfjsgq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2erhzvuyk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qocafvrg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxsfzil.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfirlri.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2advzjnjc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhuesea.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2foklbrfc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dtomhmcb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wemnguca.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2saxssptc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mubrplcf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kllrudbl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgpppgf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crjfrlcj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqexjmkk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2abzrnfge.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xcktuofl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqkacwi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qfariggh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2unyfapha.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvslwqap.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2puxfrmtx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgfslzy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrhvuag.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kobkewnr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiagyua.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2chdjxopv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbtqwqp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2utejceoj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ypadysfq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmoqwau.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kekimjaj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwdijmw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgtzkxn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2elcochmf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbqrodn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlevxtur.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjogkkjo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avqamzse.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmylvlx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzlmnvh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dmszonyb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dowtzlkp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2oiirsdbm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkpohee.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vobnkojy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdnjzho.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wcehodot.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnjlbca.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vscbtdbu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfwvsxe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggupiukm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcawlaao.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvbabdb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbofoim.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2trgjgnhg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrsqxku.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2txknyxkm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtgwpfa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nyodtsmd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2efszzuds.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqqixap.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2khgbuzta.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrtekif.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwvwfqt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2adnabara.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdblvldl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnfkqhi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vgicpyvc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jedhyuxa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbwdkkl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkjyefw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ortdwqou.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhartvu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rptxkjtw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2phomehul.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2heqzoskc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnjqrf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtkqpfh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbfzzzj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qakgenir.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzozpfm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yabiqqjs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbteohy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtwgmlz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzzrknu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2eidwziaf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgqotfq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2juduxgho.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2osdxxdkw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ssshxwuh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdvtazj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwgbkuk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nopozbap.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuygtbs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxstgca.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzvvcaf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sypqsgrd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2usidqguf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsbcynn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lototlwy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiezjfm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxilbgkr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuvtnec.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2askoljtu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kdclcblm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2beizzowx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cjujasqt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2likqtqxe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wtugbuzc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqdyasd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iknihiuo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdssuxd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfghplt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjoynxe.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzavwuy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrwttge.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlvuurm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2flzizjbq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaseraa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tywwiqhl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2febjxanz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2piprwvmw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rlceqnae.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwxsmjr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdigdki.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sccaacgf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoqinhm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhdkrpi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nauzeljd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvekget.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nezdtlji.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jiibulik.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2frwjmzjj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrprclkr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zvycpiny.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2odhywoxv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jagjnmdz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sozjbbcp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjstlonb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qubnzjhr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iswvwxnb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2irzkisic.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyrupqb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jokvhinj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrltogi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2urrilygv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtkpjns.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvggmevq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vknlupgd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcvpdgt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iembnxdh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2abuwswef.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoxpvvo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2islwwpqk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uysnweik.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmhyqxw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgqcpzk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2khkgebol.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2iexkyigi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2clrytvyb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwfniph.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrxnrjr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tejiuydj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvesaob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fetealmr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2njjrmovc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqmznse.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2eobitdhq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2patmaazu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qmypmuwr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rygfqmpd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vygidiik.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yziibnwh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdmiwer.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2frxgwmbp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dpctclew.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2asrbrbqw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xunlpxwu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vkprylto.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvkjosq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hijgxmpi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlcybub.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxqyuts.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbzacao.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2touuyyjb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2czlnbbhy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bjipbpri.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wklbmpvi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwnemzk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vigfwjln.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xfujifuy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tgitnocr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2brddyisk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kekitday.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2snzmvbyw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbcbfup.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2grztsnaw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iwowmtja.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hqribxgi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjtwamd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwomzsm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsejmhp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2phnlxckn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzalada.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrrkepo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xddptqvo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmfypno.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbbwfgb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2usjevait.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnwqbbv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfauhxr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2koxoozjn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2daihmnkw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyibenk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmcgibe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgloxif.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqursxv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fddkjkwb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2inmhxfyq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pggvxpdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sghkrwmt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvajhhur.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjdwkzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftekzzhz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpriimd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvtohzq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxeqobt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pitsjnvq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnghlxk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hewovkhv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fbllruvt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbgbbva.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2facksnnw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vouovupb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2azacknsf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuwodch.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2chwxxyho.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhfvkfe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhyogsh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkpsgpy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkusmag.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rubsonvg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdldrty.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoskbpq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtcrnkj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdlirbt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tokumybo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfajpjuw.html


<!-- 参考信息 -->