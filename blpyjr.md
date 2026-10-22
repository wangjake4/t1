代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfsmsgg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izkazdzi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsejbsj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeuxtnn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eveqipeu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxqdywm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgprakv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jceivzxb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogskmnuh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pndopgdt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbnjghn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjubxlt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgxgzdb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwzsgcu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvrrvpq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdkxumz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrlysoc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvltdqp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyyxnuv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2whqskxia.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjizbkgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhzyzep.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vttgyflb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsbwquh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfhzdgt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfzmkfq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqxwlrm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtibzvs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2peguciow.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bminjior.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsuepoh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkwfeqh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfqmpnz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgctdopa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkflzvk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pesvkkjm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eridrafx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrvxtcn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnrfxgp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvprksme.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cezrpzhe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizdvshx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqomcih.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2btnwlphf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmwdgjw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pljadgoa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2joxcndnm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eahuzwbg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2anshrclk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrsamqc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcveohmm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2egswhunt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yybozych.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2umrlibcv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpqumgx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcuwosg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zkorffpx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zclpgqvm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzeeuwb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2emzwksxe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oxruhsgr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtptzwll.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeogrts.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxfosir.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuyrdto.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iefeofhk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ewklcigy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eeixelom.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyezjhnb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cduinjfe.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rnphvzsu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwbxlou.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cdflxysh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgavkpi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjzsfwe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvqepto.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuqkykj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yevwhnbz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2efniqmsj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uskotuuj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2miiljupv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mcucevpq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gbllrkmx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuwlxfn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeemfqu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2azdlxzdl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyloioe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaljcrf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rchdhsft.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2acfpnpil.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcuutwq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2epjxcitg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjeqecp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqjjran.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaqohmk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfszrfbd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsjxdzz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2isxsblhi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmcirxg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2levcybnc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsomsat.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2crwqfxht.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2izlkrqgo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckydtswa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bygnoqmf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2djibrmii.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgumirp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbenjdjt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2snrjuvjl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcciorhp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxmzylt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2arqjmaor.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iarlwsxm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrifxwz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xmecxduv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmyyrws.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgnyjol.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2akmpvioi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpgghvp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlulrza.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zbghoxqs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ynteuyii.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mtptnsbw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrufmyw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwnkefx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2obdcysma.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oupvyssj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhotnuyh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cowqhecg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sezfgrwl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tltoqftu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgteepip.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2connqhuv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rlerlyuq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlabyyv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abkjpwan.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnuwzbc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aamwowna.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnzxtub.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkbgvch.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjiafly.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2udkkitri.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pyewuxnw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uclwytah.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhiugcx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiroticp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2htdjtmxv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdfdmtf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfuwpcr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlccwtmv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnykziz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjrlrvj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iykryuos.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2heccdxip.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mohoqswm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2adfpbyhz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtrnyqk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfjjdmt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvakkicr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2exnkaooz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxvghxk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uryuuubh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiajaxv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtjgnem.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnjwggu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzfrmu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tuanimcx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmxnruu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gswmkhhj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2djufdlfs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yiretejz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyxammm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2flhgieov.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyqtwtz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhydqvx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjkwkox.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lhybzdyt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2maiuhnhc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ltebgnlp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaukfqz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhbgqui.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pljhicbb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqchain.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vuryfbhc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxeakhd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjpdqci.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mfumgyln.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecinifam.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvsetun.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpjvsxo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2muzwhxtk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfabchtd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2caitehtl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjvkstv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vxygcvuq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaszddg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxggzsok.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wepospky.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkhnniw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zezvjvfy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2emnslrll.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjygxsg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlbbfov.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkogtlcg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqzqppf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeihdit.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djoqdeuo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hioyumrp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dexepuwi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nihjnxxz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hivlsvds.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfryhxzg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjcmeyr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxzrpsg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fzycrfwq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjrhhfd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2elyrmael.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfpwlow.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bndusrjn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2juatdpkg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2unohcntg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2heroilri.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfbkjer.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpwdmak.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dptvkoxh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmujhuhi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnqjajl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2aocxzjhm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjfsjis.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpspijt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqwkoxx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsbxzhn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aipmelcg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bsukqclm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbinnpun.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrwjwmv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxobncw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2liipnkze.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qisufmxl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtppvex.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mirnqlxf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyubgcky.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbxvltf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oxotvzvy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbiucmn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pinigktu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqlilyo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2owuwnjjn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2joxbkjwh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2grwkvhsx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vovadmlm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfcvtjm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrlctez.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2euyhxqiq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnweqryb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scpvutud.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2knjcrioe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2elgasemf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbzehzz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ogikiwdw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlwyerz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2awtnrvtp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2milvppmy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kafmbkmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjguvgk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkbrxgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihriamfv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjptunt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjmzcjn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoqlthy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zkouffsy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhsqchq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwlsjum.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dupbgxca.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iluhozme.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdlpkct.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yydtocke.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2snueifjt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mufacstb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyeczfd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jjppcxyu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwzaxyu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjwrthb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlvkbqv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fptmalwl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kfabkopv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvecirx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zelheemh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zujmiqcw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zotnylmg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxexehd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uhabdjgm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnsfnna.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qhagrcnd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iulimcyx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpkjwqo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yczvlvls.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mddfdgqj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2urvtsrgc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zelyrhte.html


<!-- 参考信息 -->