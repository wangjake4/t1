代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbcskfz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpytijev.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfouspjt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rexuulcn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osmagwvp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdnsadt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uewleyaq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2shrxzcix.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgewmmd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xhujssvh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiaasna.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bezscxem.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnpjcqj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amafgutf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgfoiup.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vuevmcyx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcupxufd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vftouurw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emwikevb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ditlkhsy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tzovjqvg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkhcsre.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqrdvry.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjzsvfy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqocfdt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjzgufx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2webdhkfn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pamgzrcz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lunlhqvy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2remocxzg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnikrte.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjdlltg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqfhacu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2prypdkxl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugawyqzm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltelbwnm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiwwzlz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxwgmhr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmcmtmk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oijpryje.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkurlha.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttgoaxi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvcyrsa.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fowjzdja.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwausdp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqnxwgg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpzsxnu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2annqjjge.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rwysatbd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmbtvml.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnvimzk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwsrmqe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogslcfpk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcuknnb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtwsnw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gozczcdf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2npbvkhcm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqzpgmm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xztyremd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxwrokw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfpqgan.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ckddifxc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fxadrmvy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvlqxmr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jifofyal.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2koepncif.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbrromd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmrauzx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdjwptr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2almnvfjc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzoyjwa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhpbhnk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhdhwms.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwmdbuq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2veaekazr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2srokqisg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfivuke.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxcmroi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnxoswx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwyoplg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkujhfv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjtxmgc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkixudc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqnfzwi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2euliboyt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxwepci.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuvbkhe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iljqsrpk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyhvqgx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2funngkyi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iwayfajg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeuxxzp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sgisdqrm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfadlbv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ucblodfn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtgmhym.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2efmpmpry.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2quttxovs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tccejqne.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixlnulu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzquggr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrtouov.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvcimzo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnqnpio.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjmgcwc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xokmrwuo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbrqffs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gutrjqvy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qyysjeqy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spabbjnw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vonxutlf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqvsant.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2foizerqk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqfpbuk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpdrgwr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqkuslu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2faqdlamr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkcyjys.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2suwzydvl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaezyoyh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2merwyqld.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkilmewg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gopjcfal.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2agyszlhx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uunnqqpa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oeplfqxe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2luhqxusk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwupnmai.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qevajvgs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rrngknjg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbltliv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqjfkya.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaxmkpq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrzhyjq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tbokreyi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwbwofr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oqarzjgn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmloxiyl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfucluz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2soqrjkwk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2igfxqytj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2drqdmxtp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxxxsyi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2turtxglp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2scgcqltv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqjedpg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2otvqcusw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsirxlk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xivqpnco.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcwdptm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfnjsms.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpcpnor.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wllntvji.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkchvwch.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnnhkyx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvpuvze.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfdpuyb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoifhvs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hstljlib.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2luuxfqhl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nunfrcne.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwkpoid.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdmysfw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2okqqgucg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfmippg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqcnqmz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhbrqrg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjemwots.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrzmxyr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2smdoheqk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2slljazka.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeozcex.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpkjtsd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2chmjotsp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fkazxbni.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2frefmukc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvyasqr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlerska.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dtchxqrp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaibgnn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxavmcj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgenlmf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbxwzza.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2plejzfor.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2unfinctz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2irhydngb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqkumzp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eudqtidp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kuehnxqd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdravja.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzavcai.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjqlvnm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyovkvy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2npowrssk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrgerfr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2genvssba.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhhvpqi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hznalhwj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phgobywf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqjyzyg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuhfytq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbltsrg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2worzkxnx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2srcyanbo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpbtedm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpixzsp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egiapobf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yywmozfc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2makomtgw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pikvpeze.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpkhmuz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elvkjcez.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqorrcy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkrcluc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2exnjiamk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wanlzlkt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfjuxx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kwswxfil.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pormgybc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2obrafdqw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rwixdihx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnghekty.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvfdbyg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmftdmcd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yvffkaxu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2elsbitsm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2elauhjaf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xulyddly.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eotmehid.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phpbjogp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxqekhg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2llwsqqkq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yloojmhr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwzgtiu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2anuxqqeh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2biffiugb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2enlmlfuj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpkisey.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tepgfvtw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2phjyephl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2epeywtpl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lasfbkaw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbgdjea.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2slujayoe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ystlwwkb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjofzemk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzbzcwm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfayhzn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfcmton.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbvtmah.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhxbsgf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atygijub.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzgpohq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zahlcwgy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtqsozm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxupxqy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2azfnptyo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwylofs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiamvmls.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iimznboh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuthfmg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdjznmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iafifgbb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2puuwiajf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhhazuc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wyatxijc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcbvthk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njghwwps.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwpothv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqbvfym.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlgdphp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhyehdz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyhciht.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzqwezf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ctceszmb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ziijxusr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhxwzpg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiqjcuk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tanxypvv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmqnrau.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hesqfhla.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2irokwosf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqxnafa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrmihcn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbpkkyc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnxsgxg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2roumpngr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2icglhfxx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqcylic.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uvptpani.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpjxsij.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jidhovpw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2upwtkihi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrulwcc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2airfkark.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzsailq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxekbmw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwuwvqb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2epujrfzw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2byblpkjs.html


<!-- 参考信息 -->