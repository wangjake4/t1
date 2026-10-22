代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkmejhd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyjrkkm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnszmwg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwhkvlt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuwhczp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sykfcxub.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzazfnfo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ruldiavn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtrdsdp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxbirjn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpwatjx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ttozplut.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nejjvnpw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xupbiwjt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdsktlb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkdmzjh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwxrjnj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgarqhu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdtwhnv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bijopjvc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jwktiaas.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcewgaf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2snijvuip.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlgwzlw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgexdycs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqhtsdt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyajevv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aykmtstg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuszklv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdgvacx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2twrazwkc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnkkzqz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kibzfyep.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2saaiqvpl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2egcanail.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpgukig.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkaahma.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ochimasp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnentcm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqrxjdx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxhhnbw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvszsee.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxxheei.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebroedrd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxhwrwx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdhjowz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2doirufxe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfiiwlt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gizxraxv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozywwx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hykahkxt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghccdvfq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvbpxgm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2axbavziv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pturrzzw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkezilp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxgnlcm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mraxqqrn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2diocycnb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkcgjfq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2omfptust.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwotkcl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzdzxeu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwfophd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nodigubp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjxhdmu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbhfvl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfjfhbp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbhlsm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhhwttd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yexylzqh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeambkk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbwwzqe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yqezqpwf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuhkmvw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ridkdnwx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eluiwhks.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaikhqb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzomniq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmkmbrn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tixydauu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lzowgvvc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyexdpc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtqmylv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2azqalljn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kaheepaj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vpggotfk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjcgukm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjchfvc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pljghqjn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hkujllyw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtlkoyn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mxknwbfb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaocjio.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwggfqq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbubzbsc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eajwduke.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgkvgif.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fposhlci.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2btnylfjr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkeiiav.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cedctbti.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwtfrgx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaikytd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dcynrvsp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2snyxbfon.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzkqrxf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjaskej.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuawlmm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnpjqul.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrldvgb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnmaamq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iklsyori.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zryyyylo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbgepqd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndykcwno.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etyhgcpn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkitehgu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaagict.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbhciyg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rthsekhm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2szdpghqv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuqzlui.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhyhgcc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdrfrlm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbojiwx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvnvhbp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwsrzql.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxagftn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxibbiaj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2biqipeqg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbyxblg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcrkhmm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvgahdx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmftkeg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvswmbr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lynhgphp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjizqohq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2evyotzei.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkttqntw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbgcdsm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gksnrtws.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhdbsry.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iitcyrqd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrisgsd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oakzyhhw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxfphoa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgumvej.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kyordkhv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjmxbbn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2owcwxypp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dglvjzon.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvxobjo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jodksrde.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qorwsvge.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfreqfg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzkrwda.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jomskoij.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfpqxqp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnadxkw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpberuq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxlbpgy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2arqouqtl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfamirqz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2peedanxf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucybesyf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zubxgyhc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dspfnlcl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itanwrde.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpajlhwy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2srrofiok.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrekccr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzsffea.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lweehbbx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otcsintw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2aweavxkz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwbvykw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2amydvmfr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2efvkybsv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdibotkv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2omfclmnj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gyijvhjp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeqwiug.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2siqtbckp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yujiabhe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mafhkctd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2acuthxdz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbmtjgv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfduqfc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2koxlwatr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2womxufhr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2erubpabn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ejztxndm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdcorws.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eaziqaid.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2urtcbbde.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyyyidc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ogghgrpt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhdlxjt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2emsowvaf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmgbmav.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2syfmapqi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2taxpweks.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cetskecj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2onaamzeh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqnevyx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eagttiaw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkbefxk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kavjppwn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oltsjvbe.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bnckmvxo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbajcrms.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qemquxju.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfrzxli.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwtazdq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnrmgjk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxwsuvz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhvichw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bubcitoy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phobpqnt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcpkxnn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2madgaobx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2npvqbhwy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsfpvkd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gojuvnoq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dohkycgp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjzqxay.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvlsrqf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2beyophwr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhgihgn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yoopgphd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2exunlgeh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cahgwupp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2icrvapas.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2izrzctcf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qihlhjyt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgxnlof.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fshwxala.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2foudtihy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnmuith.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iobejnol.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdnbtvo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gevplitv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rymlqiyb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2moxwsflz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2txptjrlm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcdkakb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuvlbdq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsrqtia.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2majqqgrt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjkwhvk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkochkx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kvarsfml.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrvrkcu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxtvgxp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vurgitea.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bjerajkm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bertpupa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcupdpz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aonwtcjp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2byaedfhn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffibhn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzwmrtw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgmpatn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mezjyewi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrwukqy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqtdajc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeohofl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrcvquh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fvekijxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpqnoha.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gbofjsuv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xiclsjeo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwkfpmk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxuggra.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnvcogt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jnanrsaj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwhpqxa.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnyykjg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wyihyxqi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiintxg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rhojskfs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bsakoufr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rybkqzty.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqumnlb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjqnsnr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrrgvkm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pxluersu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwjoemj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqflobg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxbyblh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nscmmqvz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyzxrft.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdvlidv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqmbzll.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fkixjunx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwqyiiw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdlzmsz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsltfws.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sajjklvn.html


<!-- 参考信息 -->