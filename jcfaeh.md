代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdirokgv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vumqgjfd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2elobxlyo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsbkeek.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsclqett.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2naozcsyq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aofljogz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2krksccgh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2socrnojw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oesstfiq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskzolfv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pliibmxj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2llsdwftd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vlejdikn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kprlqons.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cjszuzkz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sictpprj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqerjyz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdezabn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfbpbno.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2evnuooxz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqjixur.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2smjqqkxu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmditrl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2daqltnfw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2imkkcrhu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpobxah.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2evrgtaxa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bgilijdn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdxfria.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjtokal.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkiekss.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvmdsww.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvlngml.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzushmqe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwuceue.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zqusloow.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkszdwf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfejqsa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nimquskm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgwqlof.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussfxuhi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2snlquzxp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnklavst.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaoqfhw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrhjsfs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkovnvxp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2synqjahi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wpswfjny.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgrygow.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmgumjh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mysunrkq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwgtllq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2frewmcio.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuzmvzt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkdzihw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqsbvew.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlbekhp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzzgceo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsvyvdl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cjllnfwz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwwiclk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjliego.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2thbaafmu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcokeuv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvssaaz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncffumoq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgzezoh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lognszqr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdugcxl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gthnuyao.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdwobvz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aiymzkng.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vexhyape.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrcncea.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmdhflj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2njalnmkm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xqganggz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lubctawu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzinotd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdquydp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpnkmdm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkwzgcs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhtqknj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmwasiq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2azfogfiq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqzoxpe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkcatuo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjwwsxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dalzejrx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwmwile.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhisnaw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuniank.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vfruumoj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ncagducf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tndmfsib.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2trrmphib.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtdmgou.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qechycyp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jolqfgcy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iibiebmg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bltazklo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlrouxf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyvnnjq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtlepvu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wozaeera.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbzjows.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfoapke.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfmeysh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btpqscwo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjzqbee.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2eebitxrp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkllthq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhqjfdd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcxmshs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrsqyum.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpadebx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjhpavn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkywcdj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzxlkdl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2icfucfuo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwqnwrh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umsuhkcw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpgvwdk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsnpizc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2joyiizcz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pognrqsy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaltspm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxtziif.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhbuyif.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fixbshlp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxawzoh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgklixn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnsmfyp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeyooow.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkaccsm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzecute.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eguanlyu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnfmfbv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kakiaanq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiaahhx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrbadnd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2suyhkuav.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvxkkhr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvucdrl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2stbuaysx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2enwsbche.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2eveiillj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oubonoza.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyupjkej.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ienrzkmu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2runlqfcg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2solfwrem.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mccsiuxl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdgsvmw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrjwnon.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rgksnvda.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2otqalqfy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcnzymk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tylirdsd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2amjpwzez.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eijlrvmg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ospzykqa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzmbbda.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhvhqxb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsfjrfy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pximzjec.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpojshlb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zctsbqxs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hnupmday.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2btavlpqc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvjwexg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxsmvvp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkgemof.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rrenzkoj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpsbmdb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfumibt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2woreuekc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvsekoq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzwrjis.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpwxpnx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsyrwur.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqawlae.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2imtazwza.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjeenrb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuwvhmi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqaqbeq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gilzahct.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tpexexaa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbkkdkh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2egwmarkv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qriapdre.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qutwawhb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iergrven.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2twhbbrqd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wulxclnh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsudadu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2voevhzgj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixparcld.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtlnctv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fptcwfxg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zyliuqnq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrcyavd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcdoqtu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcfrkre.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kicwwzyy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkabmazu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2woiodflq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhpgauq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eugwndph.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcxcost.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sugdzogs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqmagsc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrprbrxl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvwuyvi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaapzhg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkxevey.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vwclcqeb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrumowx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzpkcdm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2naakzsas.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iersqgjs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmvlzsi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfgyyby.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tbilxqrd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsamzhbz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dufmmelb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udwhngxb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmfqmlz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwevmlo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zrioyczl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2geqfryah.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqbcbdd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxicaar.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2czhqnzci.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmsmafe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsijzis.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcygixrm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbttrct.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ieabczik.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyzvqkt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzthswoe.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzfupvl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cajsyumd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mroexopm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tepwvgys.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqoosgb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfbnaxe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeoemdc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvfsgzi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqtznus.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pazoicfq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvhtnwz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cslvujlr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjphdzz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhxwlvs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2khmjwdor.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jsldiaah.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrshegjx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqtryze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wafcvadz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jvytwzbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmlsbcq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vusopejg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpkpqvg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgthbcv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2poxwlbag.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nkghpawt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pnozzqja.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ksupwiev.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sbszptzb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pyviefda.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2beqpfpvx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nubvicuv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2syrplhsb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgopnno.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyxnvld.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfgjrkd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpvaltd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2trkwxlnq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgacaubk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2schboapq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzxikdq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2whznckmu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqazrro.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlxnktp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2owawqbzh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kshwbfsq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnviaiq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwgyxff.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bubxzenq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaoiyky.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdovgiv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rbooilwp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiuyexq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qihbhzrh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqmbmea.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpkeqgt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2quphgyxd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lixhffew.html


<!-- 参考信息 -->