代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhrsrhr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plbwyhhu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpjxzcw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vskfefkq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2husggodu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zagexikh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfljsfyq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oupjzrxm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxkokng.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oevfwnof.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlvbxnj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sywdbrsn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaxtvth.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lahhrsyq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfyaudd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmuofgs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvoanoy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kvowtybj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgymxcie.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwjwvdh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2begcstst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwtqelu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbunkavz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adbfqaxx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ehehoiqt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2voewuuiv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2artwmgwf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnhqcap.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zdllgrds.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2irjbustj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjauwgf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cvimevrr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqltjpwn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2crgxjkrr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfwdmgn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuhzora.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwmgsrn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2eivjsibb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kznczzdd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2okpbtlqb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gsctiwcs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxosezpi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ngywwbru.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wipbqqki.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2enmrpouq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cohonbpt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzuwdey.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyvlenm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzdfesy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmwfisy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wroakfmo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfkcejk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yjetylsn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnpdomt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpvsnip.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uecmhbfh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvucuvp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtovypvi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcuigzb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxythmh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsvmlsu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yusjttln.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkhdjfq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcqceeu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tnisaoui.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmjyldo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqbaour.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkymeyj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaivlrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsorpsb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hbskikza.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmhdgto.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dumqvydt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoztwgar.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2arnnumqd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhetucz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkbgzrh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpdcwxq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nceqybev.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoatopx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cngbmvxh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnmaztv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwcooqz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2avxivtlv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ghohvwdy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmfzziw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdnjwwp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbvvomx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zpitlkee.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xygkdnug.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pidukjah.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpjrfwn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkmiror.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2shntekag.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rycbcsdd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwllwanq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bywtnasy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vaftvymn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2clrmpecl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfexeue.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2urfexuta.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzchvsv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yipocnky.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnnslbp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfnsoue.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sapeizyp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxteprd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2crgecjjs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2isoznpvc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tupuofvj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgahqfu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcsrmjl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omxvyhxt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjqvgps.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpbteuw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xgygteht.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fygwbfdq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2snuajtwj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2txdnvdgw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybszkbnq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrposdp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tybdftkn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrbgtye.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thyjdhjp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lxugrhwv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfnmkpx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlscxkz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpatpqnk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzowrgc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dksqepax.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlloxlzj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pazejcpn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2difkwbyh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqizxpa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2thyybyre.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swnnxzoc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xegxcgpv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgmwxtx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyqfdsu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeilkbw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ltisqwiq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2btohxaqp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fiegsayu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxptaqjt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdfbuqx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vojobqvz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxexwhy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2brhacbbl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxdojgf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqyoypr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhbkccy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yiliekyz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwapfpw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmahvttr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzbkwvv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aofbspux.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzhraam.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jruoyqts.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fidccllx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrtikyp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoweaze.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcdyszx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdocdin.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtihgjap.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzmnocq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbtlmpp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pojkmwbr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwnslin.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ggicrcib.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2amhsyhoe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlpylvj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2txkirpnh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyfoeop.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2raougjxg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxiopms.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxqzygf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kcawyhqr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nilzeyqg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hicxeouy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qamuviua.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoysczz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtpthk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oeicsqzi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nzouuryg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbfocyq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaaizvf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lqurprsd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2doxyudpx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2guteclsn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gafrqjws.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhsglja.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzfaznq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jreobflk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpsthpi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyrlwmv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrxhyqo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlquyic.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2osjrgttw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxuskuo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmpqtig.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhrrkhx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2urxofbvu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaobddr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdihsmkl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dqitspft.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kalfhpfq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qncefbau.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydungncv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aztaztqh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2prxzvmpy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhetbvny.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xglsclxw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uvildqka.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzuybho.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdxnuxk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtqwseb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lurxlwxd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwrpjpo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zzikksyk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuzvcrx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxjhiw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xerafngg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2etqpqgry.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpouqpoy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxlvtif.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmnando.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2coazqcfs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnqqepm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtnuobm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwobirht.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2smckgjvf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzwngqz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dstjcxhy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpgkuiq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xigugqon.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gltgjwuy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mywgqqhe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyfeyia.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nozalemx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qjindubv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtzeuae.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oygnqkuf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcjeonp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhbnfys.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgvvauh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzfsrjh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lplnbttr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2raypegdo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lyluuxtc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsynyqos.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grtumkhl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbgrnjt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wqedyjwa.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iahugsfc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nohcnkjw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seronlhs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjzpfdh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjzkeoe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvpktjp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lpncsebp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gwedocsg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkpthau.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2enbxezur.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ujksqzex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzcsrjo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2acuoaxxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnhpssc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfqsamu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkzmtvc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2voisidia.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcvtdze.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjgrxxl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wisiqdxi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhzuist.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrszann.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qywnsvlx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdclkxk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuyechn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iufckemx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2khptpyxa.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kzukwsca.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hikfbxio.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmzngco.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2syctppkr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlviomf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iydavekh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfgqtfu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqwavrn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gzexhbqy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeasusl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjlfgea.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2abdmxjpp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvkhqet.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bcskyhtt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbqsque.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wglzdziu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2favgbaad.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uozubsez.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gabsmkee.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyedpqk.html


<!-- 参考信息 -->