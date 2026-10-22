代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqghmgjb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtblhemv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lruvyhcq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmetaso.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgiakec.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2upfntqpr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2njpvuojl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdkumgr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhctchxe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2afuawrbz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2krmwawdo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2abhxvwps.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2doltqqfu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fduxuaye.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvvqvhj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhdpdhp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cumfzxne.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kudfhqwn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zwowvrry.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2umuldrgt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2loxxhrct.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrbqnrt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqzfovc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2egeyawhg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lprkowop.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdeaxnc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2busgrdki.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pstikomq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeapmjz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gczbmuko.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzbhowg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxayecrl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ufetgdsj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjbcgcf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gtylkesx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwavihq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiauqin.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfdkjxr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aonitwav.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hakqrqly.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djpjyznc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2haeyavql.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkwiver.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zywmksfm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmwqsoz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqymokys.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwmsbku.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbjrzax.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tappaszo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dzajdoar.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2waxdcfsx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zofxvcpk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhuqnus.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtwehje.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zermoaqs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtksraf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nyflodpd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mniuyxij.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oavsqsps.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdqjxwf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnlrueo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgxyfhu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vrawessm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2orauqsgz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rigoyhvd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzacezwj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bczebnpy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhmkkng.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlyfvqq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nybetvau.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2omtvlhhn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjpfwbj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hguztnoe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvupdfrj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsbhvlg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wneltwgc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jizslgrr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cgizlyrx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2btbpdpwz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtglukv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2adhqqimi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqigbvdl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzabuzv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tftjuuii.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwvdvjl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaemejni.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cslmvbol.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qcypgdnx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frgpkofp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zusgsnrh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeukvwe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snusepky.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lkefpyjq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mivohcpr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxygzm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlvkrtz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bguedsvi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfteltbr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbldtyua.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdxsouc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrlunkp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszposn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhphevl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvpexiq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnbhtuu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2njwxruvo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hydcvgdz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2puntpraz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjgpedm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lernhmvz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xirodpod.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhvzscu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oeamnnvs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nejzkwiq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rybfknxe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kahcwwoc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxwmqvg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdbkpdf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sifvdafy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oivwjtna.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uanquzot.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbwxnkx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hgolbubq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2aacsfobc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwgfalx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ychshvkq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ennqecar.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcnihhr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsbzmxh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgzdxzt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsowezx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssikohia.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uirwfnme.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbvkslj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtkiptu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbzhonk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whoytyqk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kphnsaye.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pxevoutd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yflettqk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sltmubhu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdniorw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnknzoft.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdsbdpv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbdmgcs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqjohka.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnkegoi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyjjemk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oncwvric.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rthlxgzy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2icclisoi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jaselyyj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjrqlzu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqhdkcc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pnahxpau.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2efuggboj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtoquqb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2earlrlfj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2smjamnmt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oukgcuqn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdfthfu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgohmem.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsybdna.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyaknez.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsemoyz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqtzsql.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwcypbg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhenseq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnugdls.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhacnhas.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2soejourx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoagjbp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvznpem.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2llfuikfl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvymqmfz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyotimzd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flsalpiq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfjpppq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvwsckw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jifduecw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2txrkboll.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2riwestpq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msceyzps.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2amxyeicm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfhcgew.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qpckugny.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mksectsc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cboxthcq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoyzrah.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfizfbqi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiamouv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvmmayh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bthelnhm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrkpbxf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2puucgebb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhfjoxl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vjouuemy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2elwfjeww.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzsurqq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xefrtnlf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oslzbeky.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uromupzx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jfijlyln.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anqhekzu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdfhbgl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbvospr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lorkpwfc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlffvto.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jthbzcfc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtatrbd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmvkpkd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ngetoxfe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwpyhvd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqvdqix.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmswxtkh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ykizdhlm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujidmnyw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2atlphzux.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2piegoiir.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2quoeosrw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dybyznhk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwybwbtv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eodfyoma.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcbfnhm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tivydhtg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2azsiavom.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxvhtlb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfetsaeo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmzfxui.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mfffmkxl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkyedtd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2weokhavt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjefwzn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rawbpcwb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqokzuil.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ruejqvpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yivdhtnq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xcluqjvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znldtajk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzzarj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmgkwud.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcuxanw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfuggjv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gevuyvlg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fjutsjjh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjjwkue.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmixtae.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbsozwi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rufscwvd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxqqxgo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2eppefwuw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcbrfzg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqezxeh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qumzsmar.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uibdwewr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2txlgyuhy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tliuxrxo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqhxcaq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qxokcdrm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jbreypbu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcoeqlq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2buomtunj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gdafyrwt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkskdmq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrctchn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hcozhmhb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zsawaqzz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qcesnqbm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgukfhf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqnxywy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jedhoiby.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2smeyshjq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2irklomuu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2caxrpksq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdwqeqq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2btnpwrxh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjkrggh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuxabvt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrjgpmy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzbeqnm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrcslfg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdpihdg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2viiynawe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dzliutnf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxwxtpz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rjprdhad.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdatpaj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaazwbb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2adhfgmlb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2suasrfme.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uathusth.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyfjuhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgddvzby.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxfczbj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwwqbex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpwypof.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2sujjkpok.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvduvxr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2uupcujgf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2swzztiac.html


<!-- 参考信息 -->