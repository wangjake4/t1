代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtorvad.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2odgevidr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqijlun.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2deavecgh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jckztntz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2anhffndo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auojumur.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fbskzczq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2furtpqkp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2apkvuhdc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwogzrsg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tnskikpz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qreasfzf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxuukwc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrndtjq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvdfrhm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrekgmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kedygcfo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lolcyavx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuqdivu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xprlborg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzseaov.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dckgihhi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2boxflodt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhrcdzk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2geukrxkp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tmooqsua.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhtxjut.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2okvvnzxw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gepzxxed.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mfumkyii.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiyewbm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmnhcpi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsfkebk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqodwjq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuchjwx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkhwmep.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2alscdsgq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfllhjm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2omrcawrv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wakcrysp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpkqlkk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2apulgiax.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zidkqyif.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfthpse.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrrvwcr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ansqsqpf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vanvkgtt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2eycohgwx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iucojhmv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxdvjhl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoraqpxm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qwppuaoe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqznlfc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjzulpt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rromggnp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zttwwcla.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpistyt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhsgjoq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlgpwcm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eyylphar.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jprubcjg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rljcguct.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjzawsi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vluwcrqn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrnqogc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yowogwxd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqoywxq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gncoziyr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbamaglb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qqudtsaw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2eenprvvv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fafjsxep.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xicesubi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzyfexk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2evnciqik.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nrngiedq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gowcqsrl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqkgyhj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2agkbapyr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nexdiery.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2avynjzbs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpmcsdm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2czwtcrmk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2eayypknr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxbpiwd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbwdxra.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqguqqll.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwvasqu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgkbcsg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2abfenjxi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqecxxnu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpixuxa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjbrasv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2timpqftf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bzldwzde.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2drvclxdx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbligvl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2usjectru.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nupzdlrs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmvirfl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhumkey.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dmejtbqe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcwmpeb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqythvc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfolbnio.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuranhd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqhpifh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dudiupds.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uldmeyav.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uosfsdro.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2iytfsnfo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcyyfme.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jtplijja.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nltkkfjj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgydjrok.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qleqlzjq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sthwstfr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2etgnltnm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egjxupuf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2efflimfz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2llxenrsm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2licxnhun.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2prcpuuns.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgxcvwp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwnpyax.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2biywztvo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tistcead.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2skdmocop.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2stihgdrz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjcxkyj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jawfqcgi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbdabtm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzzvkdp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2exfucegz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kilrldws.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2szxendlz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rflvfzmb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxlxtst.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrpcyos.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgardch.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2koluuren.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tgelgjce.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pidiwkug.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkatrblj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxplqmf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2duebklzb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoefenj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bnehdfri.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmlqwle.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2knogiwfa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuyozqc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2scpocmpn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sykgwqub.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjddhtw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjluzvx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2luuqimou.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nykcnnah.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nrktirls.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lomfrecv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmpufoc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2harbyqjd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nniyqigy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjsszbb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhaozhy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxjrunr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abosuiba.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ximvvdre.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhniqzs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gimuinmy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oqssjbvn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyvuyzo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2trasalbe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2reiggmzl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrxdxfa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gwopxqnr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zccpyluh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cugexjvf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwmybgl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjovyow.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjdmnzm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtkgxpo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jrphxmgi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dftobmnn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2whjeenff.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2onooslpn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2czhuzpoo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2frpfdyoa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ktugzbow.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2awfhbeon.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qaefgwbe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2esrfwism.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtrmbsy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qejlmsos.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eztndayw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhniayu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zzghagol.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2phkzfrbq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgzlnhh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejciapwi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2icjsncyl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kshjscrk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2quojnrec.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbdccmk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckykqvtw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxizot.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdrqlva.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhlbmbh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvfvsnp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2trczuuik.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrqceoq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpithlpb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rowzirck.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fevbfpkx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2czcgkaoe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2clfrfevp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfgzxny.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rddfjfti.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2imdwqtlc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2crjutdbe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpdmxou.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhhwwsv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ktifrlib.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2egbrlnwk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2axsmnmsh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxykewex.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rtitsfll.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdryowms.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eobdhsti.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnufyva.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnlqlpc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2unbpuejh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qiidkigj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxhmgzj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ichkaqwa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnyjymo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fascjpyt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yclhefsx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sfseacco.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rxappixg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqhxvxl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mutwnzaa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvaikds.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dznhclxb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kdghsxlp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2okvtudma.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiixpqq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvexnak.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjjcrqv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vciiwjfl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gaybbnls.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnevpoam.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jewlarko.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vveoeaap.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiennbr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcjhkdy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yylbsylp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vyctrlto.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2viqylshf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuqfrqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrhezqq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlaemgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evehcirz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzssjry.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yedijmqn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2flpnkfhb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkssjzp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2toilcrmc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwqypic.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fogrzivd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jotthtph.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdqynmr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzmphtd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cimzdqje.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxzytvj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwxdtiu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bfearfhg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2daddjafw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dnppuzrh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmzikbh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nznsfznv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoyhwdv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2prahwjjy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ismshczh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhumbnn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuedknq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlfltfe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2elsvgtef.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xgagorsc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjqvkdh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qclzpdaf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwqpzhu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzehrpi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uycdhnwj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rynknubw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nubnunjg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2opgpnrax.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zireohot.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdtatii.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiocixp.html


<!-- 参考信息 -->