代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfsuwys.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfotviq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qoerxcfq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2znlofztg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2egtjnaqf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2avlbrboa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xjykyxqm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgliobzl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2azgpfkst.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgmswfg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2krkpyvjm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsilrimk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2anfgkqob.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kparffxd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2extlvviv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdtjxeo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbiumiu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iendkahy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwfohhx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmicsss.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhxtnud.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rghaciwi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apetgnem.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcqmcbp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kzljiiku.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvscvmzm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tikurlsy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmlkwwk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mpttghox.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fphftyrv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2quvwuuru.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhyfhzw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hekskcap.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2liarrctt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eaczmewd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkubhoh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pechuzin.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqqqppq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uosbptjp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2liwabcbm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arfbdcve.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiqbaml.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwfqtzn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2otantalk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mttfpefa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2usquikjo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2azdnekpy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2smdiawel.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hftxprdo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiixfkr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2utcngini.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdrbyjf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwuffqo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqboiry.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqpqwvt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crfeadwc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnlysrk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxpmspe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjckzzf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iytekixj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2whtajeht.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxnqijo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvipubxy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2poejxjal.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vapmhjzj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2efnsagmz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dokjjlrk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ethlqvsa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2usdlosne.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqygmhs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pygsralv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2neazursn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsijnyx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxenyas.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvvdgav.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsvsldw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eladbhqc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gdebfkbc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmsxpwj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjozwzt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mpunwvgm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyepcet.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsvpgov.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vswtwjfr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvgkthi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypevuntp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ificprfc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2babngrqo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yoviqrjm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwxpgzo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2djjusuit.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrcmvxt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbjkbts.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnifdsa.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbtpcnf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ervhddts.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxlinil.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gezszkwq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eombnmzm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2updtafan.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnywfuy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwehgldk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2srzhzuas.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqocfihc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urniroas.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrdavea.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsdiogq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmkrmfq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czhwlrjw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kidibfyc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xkznqqur.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdizvrt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgryzbf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnsnzjn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdhpqnk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zheaxgiy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqcreou.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnwpnlc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpfkqqq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgavczwv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrfutwp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2awwqkztp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvreyqo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cykanaov.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhdqlu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onpentux.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yodsncwn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmevyig.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2szbcsojr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjctoas.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fwarpzvj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiarqlt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtuhghe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lopurhpc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lltfefhs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2laeoshkg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzhhofg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmuofui.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2updmdvmt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jivlerkx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mswmjefb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtumrnk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aulebkmn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqohvuop.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqywrbc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvnwbiv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqlmiow.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mflzzfba.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgtvhhq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uchygbil.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mwskjfiq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pppivibg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ercwoxtq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmcquln.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dzihbwjv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjczprm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2alvxvasa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bilttbek.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iudvnxfa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmutlib.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ddejemle.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjjtadk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyuqkwb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrhsrpf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdcrbuz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jawioqym.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uxulmwyw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2djuxvjpb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwpjutr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qifvlpid.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcvomcr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpidpbb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfhtoza.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwjqcli.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2khrculdf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpxyfou.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jhynyodk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2imniuuck.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcuaehl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nczwwfpb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkknvwjn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ordwfnnj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duxhwztm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2myyddead.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iodvgzqh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ochqjzil.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cvogvyug.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2naipllzw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2epwtkhlk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmurlll.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nwywyqhj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vifigvqk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zexekstk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uufvgbmr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2helhhfpi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2muolcmwl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyhhovv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzaghbi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zmavoaae.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2myztddab.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdcmyu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2itlcxaou.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rvixfkad.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjojninx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2trrwazst.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxydyxqd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2amroraov.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbfccov.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgctsts.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijarhchr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2drtcybix.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2emmsthgw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xnctnojf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvuxrji.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2keqfgjbr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wslxxqpn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgwxxua.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvjwqhs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2akifzsoi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnynpmu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bacplizr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiejblm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgvpyvz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnmjlhw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2semubruv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfdypwt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnaxmii.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqkzlgh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmrjsgu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhzztjq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfttzfr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gstxxscu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2plgukhxt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pldmhxhz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaneeakt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2sajycmsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxqpeui.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uayirpoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mahsxuda.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2iyezxciz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuldmzd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lunbcpru.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnsfywg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2byxmwitc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzmsihh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bckbmcnt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lamhfvqd.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyxvjzh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpgjnuy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kharfkon.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rxinseqa.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2moddlacn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qaweljyk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaomvra.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tlagqotl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xnknvmfs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwrusdj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzwgsgw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2anhzvjfq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2skhpuqkh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxatddd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsixfdd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmnkcsy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gtewrefy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcvuuqf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkdylgk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgnhfyz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2csrmmtdp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wscuptyq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yuklpzyu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qmruqrlo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjodnwc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2epmpwmzd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2guzjfohp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mljfonje.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbyoduj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mszsfcva.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnzmpvs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2orndyiex.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jefoqxkw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pvffadhe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fckyinoq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mysfurun.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2culvmpcm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2opkughtj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnpzlhs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2znecmvnz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpickjxm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2urmxaoob.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhhbogg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2weooeyiu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2grcmxpjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eruekmcu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjemzhb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoulghs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tonsfrle.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fygkhorn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpjvyzm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkriglp.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oinjvmda.html


<!-- 参考信息 -->