代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kczhtzue.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acpexari.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgjqjhi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2joksguab.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfivgbuu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqkggdk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fblchmwd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2savdbfou.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdnczul.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaxukrf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vurpdjcx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmdgosn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlvozby.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2latcpcka.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmrivcs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fgujkzja.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljhdblr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdltdde.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2teddhxbk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbrjwhu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwrkcdl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2usuwtkxf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdedegft.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tabagzdi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gobwopxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhamvqen.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ildnbpjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wapnupkj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rlebkuat.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeptpxh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2udsdieea.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izyjwrbr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbxdtjy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2reezvnox.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnnpmhw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iyupzqba.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbooexkh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2veafojmi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjueusm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2varuvjhc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qypaspri.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvhfjzu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qylbqccs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqktqsul.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzyvkav.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvalkot.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2spddphat.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsziiwac.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvaqcbm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrggjrck.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yenkqapi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfdshzr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcaryej.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2etnvgglt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkrcaav.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoxgxoy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2asyzqkts.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbhhvtb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiidvlb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxmqwgx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oyligkzr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtlaksp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjkjrvi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjpazlt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dthsvctv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yivppclv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dggorrcj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhtedtg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jowlbglf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wffdwclp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2egwxnssx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uubjngwa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oonnqqtl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvzqtav.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vryiryte.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbmpmjl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaezirg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtmisnv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vxahccpt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghakfopc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2icllfwun.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wziaxaym.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnskpeb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2srabmcth.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oojwiokb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsyzfvq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsiyflz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2scfkznpj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oelcqual.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cnourkou.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkzidbn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jedtarwv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhphzct.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxhcvcv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcwynza.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2oterbzoy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdcdjzn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsonvri.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fiftkvrx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bucyefnh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeckqcq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ffufdnnb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvcwiiz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxcxvbc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ogolvbid.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiwrvqu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxrasnb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bylwwild.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzqqzcj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sjltpukb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjryzlp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrwgpvl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxvqloz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfdmnao.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2luqhckpo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwzjenp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzarfgf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjicswh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rleltrqe.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwnyjuk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkfklfr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhzcxkh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpsswuo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbhpywa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfavfph.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhmekjj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwbukck.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oebfjigl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xdskjvzf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2npganybx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqdxupb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmrobir.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvqzktl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtkrlms.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qkowovbm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjflhzdx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2erwpotbc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rocqnqwl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2etncgoyq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2antgshuq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2arkpukom.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snkaijjs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwjsjjb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbljbzg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgoogzd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gobftvnm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdqcfi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjsiryc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2evfaiuun.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hffafdva.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtoqpmp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2byxjdxrt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgdehin.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzmywdn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npyjnlrr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2slxofcwu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdxisyw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azusdygd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkunqyk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxohrlxi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvxrjyk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqtytlh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkydkdw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfwcwxo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtniigv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2giyqdhws.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kikqqsrr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoqbnlo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2timbiwjg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnitgcpc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2shrsrcgc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyldmpt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nilovwnx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpfaqto.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duqbkfpr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdeohzp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2otamvfsb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uefyosse.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqalffg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaagnnar.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkegvus.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmuwjkq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjceclf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwohkok.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fsafbqbc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2faygsvws.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fjozinqp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvwkmby.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtvujvb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzqpjbh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzknpvk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2icrdgryj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pgludxyk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeumopg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oenwghgh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2owfhmkre.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbhqhwf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmikjwr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cppnydas.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwtvakk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoapnsf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwstxfc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxgnadc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeorhpj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eetwfvlc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xglnsdoj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dchixjwo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otasjlih.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbpdyaj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2otelvfiz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwkpylf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymomgjgu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhndukjo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdtdknk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rebovfzn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnylxmbv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2leensvxi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2imlbgigb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbjnxil.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzqhavz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vevyffir.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yamboqrk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxruulp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ijplknrl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aveurxux.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2egpbivjh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdpueid.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wphgrzdo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntptmxik.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvgcuma.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyuxhok.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmglspms.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpaozxu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2famdwlvc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2janqfrbe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2efouyxcn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2evkarlvd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nliusoyp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdmmmfq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdkudzb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtcqtho.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcssfgcv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwetzso.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhjqytq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rbewbhoz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2litrgkvs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvkryhn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qghhlbaj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mivdafwp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrwcmah.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqlnnoh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yddeycoe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wpavfevm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqmclvm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkopeox.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtykegqm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrgvxai.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqnftjx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2szayliog.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rojptqxz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdycngd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjzmvav.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2otduiqts.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2subkzoft.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hsluvjah.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pqifzidy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2skdayuea.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjfbzjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sytkoeuw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqtztjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmigxosk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnenypw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkkmvez.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2orzabseg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgmitoy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hbccbuil.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeormvo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2koohsspa.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tycgvfmi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nujkdksp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2khplxnnx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2movajqwx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2aanqojhd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nyezsxrk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oqatwkdy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcgbpmk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rpibrcvu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzczjxa.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2puqsrnxu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jplfyyeb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2plfmgcfg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pfigooah.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaxakmm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vfibuhcj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ianksbpe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2owpeflax.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2snhmnfpy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bdskhttl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaoskds.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqrwmun.html


<!-- 参考信息 -->