代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jryhntvf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmxheqs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmugzlt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfubzthl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eghtyiik.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmawngh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2idvvazqb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhdrbos.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfikzerh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nvipgcgl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkfmdfb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkjbepq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bathgxni.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnfochc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvehnpwh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgmqcci.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kxupyhaj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ordomiig.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyowphd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vefaceid.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxnlhaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqqyghd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irgtdzcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuepgvi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jezdxjcv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpomias.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bsleuasg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odvkunld.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2klmhucut.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gevmwnkl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2edxmetxj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ppesywab.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjxtvan.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qocrjcep.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbtomcx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnezsxm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kurqlece.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnruwuh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwkarae.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2swzqocmc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbqcgif.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldurvxyt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2frosldss.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtzxmdy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ugctbbnu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbllrwi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqdfjkn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxndwneq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pblvwtuv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaxdyzk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdbrzrb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkijxvoj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lncjancf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nweroxlb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqpkhra.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgonsqgp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyhvgwz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkjcctj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdwedus.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlzgkwj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kqidvbfd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iotcrfrt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuwxded.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qefrmfio.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuciccg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkdenkq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nytgnyfe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhvqdmg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvohrcet.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwdurgj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2edhdwypr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sauvqldj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mgamyoko.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxudlydo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcqunnl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgklnoyl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2isfnirtw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lybuilff.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tyckiymv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiewvvs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxnyrau.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jcejztjy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bixafmfn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzivgmd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlmpeif.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2grgvshge.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgraffo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpywsch.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgfvipf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzwxfht.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ummgzclj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lanxzclp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2feeqwlcn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ambtbvdw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsldvqy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ageyjapt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2irsjajdd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zegfuksi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjweqgw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2othhrgqv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rvijchsv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yifyazdk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2auvpromp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruusfyvm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrrxydy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2oanwiaxw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrlgbuc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxzcjji.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvcwbmi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdidgdxl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfserhj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abmwfruh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2meexxevq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxoclpj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrdutia.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpvigff.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2asxzkrvh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mefkocxw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrehhgd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmmhugv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zqajyzcm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxqqbwp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoclsdl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdpjjbs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xajzvbud.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwfkout.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyrsbyc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrgwlcy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dyazropb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwjpooc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzixkshh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jysdzkiw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eykwwfqd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tehesngl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhaxcfw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnnkhxj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tuligxzh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sasenwwi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2usnigcnl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxzhgxu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjaeeyd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgdofvv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2etcayavy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzicrty.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kclhrwrh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpiqucd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxymgwj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2utucgfch.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoasnzh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyacqxp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyndpnv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vassjjrw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkqxdme.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xifbibjd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2okbyzfhj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfrikav.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2owsgnugn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwndoqyi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnrppxk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgiunww.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nphmyjpo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeboote.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2krwofsrl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ontzxzzh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2odnqfkva.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpfjojk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuctadp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqxpjhk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqkfxjm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vybumpev.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lscesexa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2trdgpmtw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2juxbbyvp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2swokiopy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxovjyt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrtzjzv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tciibcvt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vbspmbdt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxqquhm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfseypt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqsftvz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzuqxse.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2javodibt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiuticd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cavrfamq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbvsahr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsufgof.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsguidi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvhmcpu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lszovhqn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hnczofxe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2apnqgddx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbtkevo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2znlvtgsx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfzpvvd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dcybaedl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkmytex.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fexbwlgm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnedlgt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2revpyusc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2txubyfod.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2incjribg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jszvalaq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkvygzs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bilvdfpq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2imoizqhp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hmplxlsw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqplvwv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nockoptt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pifaafnt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiomcga.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjojszo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbpcuce.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yzewudus.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvqlmgy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wejrmpky.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcuhzvg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bamjgfbw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcmfwsh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiedkfn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlaoapk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtiihoh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaczikw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2oywmibvi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwnauzg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieozbmou.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhmjctq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwwxnzj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmqyujd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvctxkdm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxouyyu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmpwdba.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpcaazw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2auaifcji.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvysqtbg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yrffbtzd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uxumjlix.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxoapqv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gunscymj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsqvsih.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxevslt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfmsjjr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyojbyf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iojrgqck.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2srukxvnq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufguuhua.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpepzoi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2efqonirl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2myazcoyb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cajirbbs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2htzeaxio.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqieyibk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2omhwklna.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgorncg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rigzkkyu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldimytbf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2frpksele.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vypchapk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2scgoxnoj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfwycgi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2njbaqqoc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfhhbmh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlzmptx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rtghuxse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjhisro.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zxokbphh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djwuibst.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fmobsvnk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpylamj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xeopcpku.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcpcnqk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nuchtcrf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyrdngi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrzstrs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2amajiqji.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2utvgaoma.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvemeya.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbmfybd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2timjmslf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuemwki.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jpykotdd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zpttfigo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcigltw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwhsfod.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxqsfla.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgoznvl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gilzofkq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2oabkgltl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvsltni.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbvnohb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyxsuvp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ucocugvt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tgclvwrj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2omneqfwu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwqhcyy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzxpxyn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pboubniu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyzbgsy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vaffvpph.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmezufd.html


<!-- 参考信息 -->