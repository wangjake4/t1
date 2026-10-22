代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmrwwmj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpelzbw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfjejf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krstlvdd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxktgovz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlegcpg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqcgbvc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mmozvlac.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhohbiy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjtpeml.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiedtvqp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mshmqxiw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfuqjfw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ixplhbkm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjvivjs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gndarobd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2crlxvhte.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkgmoqz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkovcfd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrkrveo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsyxypb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itvxalex.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqhcpxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2habqgbgl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcqwgay.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dphtejms.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zukgjnvx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzblaud.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhuaucd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cozjituz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2btqterrq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrymytf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2awnpulea.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2irgoxagw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iexshqzo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhrrqwl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibueoadv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnjuvfy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuqoefc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2edlmhyhp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jeudorqu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkydorzz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xijqdhfd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnzjpyv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2omtrradm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zznpwbsx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsvunew.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsrqqdw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmtcpad.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hevpznud.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvpsvbr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlimhiw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2slqjazgx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hraubivn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbbfjou.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gecdqlud.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2icipzkpn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qizugubd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2imlcadtv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhojjpzi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nebvdotj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmenjdfn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2opquvzsa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmfaqwa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgzoemy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeuofyi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wckgedif.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgwwadw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwadryg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfsbjsw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2orlecjvt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyiyzyc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jojqmkoo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhbnnjk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcmwkgn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzanplow.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tamrswlr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmwhjqi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzuyxuj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbosowo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ryblyjor.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2glwfdmeo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dczpcers.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrdnqqw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfbgute.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2smyncpzp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2laoehlbe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvaqywx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnbvnsr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mylllwog.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnyhdmr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxxanld.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nncdxasm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpomfvr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2midpydsd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvmwqdc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xznoehwu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lceavitn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2scjdngjy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrvhout.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iskcotfc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeyqnou.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuqzbbp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwrovkm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rmevwynu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vdelitnx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvefwfo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqqyhpo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kpljdfnb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjisqaiy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lysgcqxe.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkxrewn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oosijyew.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aybkizjp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyeualu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fftntcmx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rikplsle.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyeqtzd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tombqson.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsbgkfg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dknetetz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwosigq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxtwlwd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miksqmwr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xgovtarc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuaikry.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brdcgknk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkrcoow.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sqafysxz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2muaxjlsb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfqxbqg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dppbvojl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eaifixpt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsmtlyx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2odbnjchg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpqwyun.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lncvgcgq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2coqoupkb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yytoulhu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyegpsf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nisqtezb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfdizjr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprprjh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjzhiaf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhoqxii.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vplgarxt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwemyxo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnncuas.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2btjemyac.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xivxlzpc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnztwnn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvfeoqb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqazdry.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzndjufz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2imopwspr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2njonywwv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxrjtxo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaqtluk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2smurtbzc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdzfjsg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgftaztm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrtfhvr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mykjikvi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfsgvzx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvpcphb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2enlzmetr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lwngbigj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrpphuj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcdfpsc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfodwqzn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cedripbt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxvyerm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2czawqkyt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwudmyu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2icgynrkz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaxyiuh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lrltpjfe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnapxzm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbemvup.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxwdeyl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrjtnfh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqlukpu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjhvury.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2alunzhqn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2anqmyfeq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kecgwgud.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnknqov.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgcfeap.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qicuavoa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lueuwvkf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2orhhaiqf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeefrpib.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsuddfd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tudqzfeo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfmzulg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hiproaqp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gofjmdkj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmzxawj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2visqpmii.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjghepgu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wbysqbbn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2guskepht.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twxhppyi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqejdyd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzljzhs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2scbnzgmz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pptpnydr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhyirev.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzlomrn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzbvrye.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qadkqqak.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeagwnat.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2egayotwh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwdmtqx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbalash.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtwquhs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2auoexkjg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdetaux.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrerdqj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlinwvjp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gexjqhcv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnadvam.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcavsig.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2awowdhwv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqqmcfz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdoleyx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhrbxnw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpjtqry.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzorhni.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlcthnb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvdthek.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2leylxvyy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nvutcmet.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjluxjn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lrptquiz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2osccyeve.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqflgkg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzefaet.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zduzebqh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vppcsbnz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdieoes.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsgymro.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hryhsmhz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hevxkzwx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2drsvpkom.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sryerbei.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2atilhxip.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2shlowtyn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfrqjsj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zilobtkp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ucesbbwp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clxlfxsq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vvllplgm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzmaxdd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2belzjdrr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeiecjc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xzirnbsg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2llruzbxb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xrucevxj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfsdirc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvhtaks.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxfwssh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvobsiq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2secqyeia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hppwxylp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxrojgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpusfyou.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgqnqsf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vypkvols.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxdwbob.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqnhrlf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaowivh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnflcgo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsxnjos.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2molmfkxz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rohhgibs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yczldcjr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyjbtlj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qkltbpki.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vawiivqk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ugchfnpw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxevisz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aclrdavq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sukqlinq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqbwqra.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhshnbh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cegnydtx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlutlca.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2evpjhctx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2usqyyoqp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzjmdqy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2isseuzkg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcrqwaj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhkokta.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ktagpjla.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkxvzwt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gamiraqh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbjphwc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vzspblqy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmkfsar.html


<!-- 参考信息 -->