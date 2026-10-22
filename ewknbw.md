代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dyibopvk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqskfllq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgsvtzg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2taygkjkr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaxuzfm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2thgzijet.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yedjtlqs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2evtkisdx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstbfsvs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2srrknhvf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsnygux.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcvdkil.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vctmudgn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dcshrhbq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jibpsqtx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyuazjs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiislxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfxybea.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2demapojo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtetlxwv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iigjtmop.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gswplldx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pvowgnhc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpucgpr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mewixcrk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcksizq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2huvemmzp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uttvvpcm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqplqbeo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkynxzon.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhihlxo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdpyyqe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2elrvrmpy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvghiee.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsjejhe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mviclcpx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wftkgdlc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjewjakc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrsrrca.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvjwzjl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnbqumy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eogzzcxt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bppdfjso.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qparkqdp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxwqwrj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfrkzkl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcymqth.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xybrtqnl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hrniprnb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqpdzam.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnxjirs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2flkhufxr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rsffwqxy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqyartk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxuodmh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uchfrkvn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2opaaqran.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwignno.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zkreqitx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gchpxuby.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zssljkca.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzkpfjh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnsjesh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymizirgk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtqkdfn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xwarhfvz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjzsdfb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2txquoeyj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ywogtzie.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nokcezhz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2stvhxerw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlggucop.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwbxvxe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiuicpq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiaieov.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2omrlkvcd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lysnpall.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqnnqcj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qakqtzxu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqcjqth.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rufiweda.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbajydk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmwqnmg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcqrmfj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2brplxoxb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbiowhd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yoczudth.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsshjsda.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2aekeegca.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzttbzpi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2epqgoezc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcrlzgf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgedpvz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uptskjqj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtkobmn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2exgjgdib.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rcokzxkp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2awnprroc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rwayekzu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syhchehy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ezclzykj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwsquil.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nmksaowk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwcscvf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qreedwsu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdfcwld.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfqwdvk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ochvfktx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcxowoc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imfsmnfn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grlyccok.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wptmbhia.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngksovog.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlucyse.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2trswqxbs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpmdltg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdjkyvc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhgowwt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lfftwftw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suifzxhw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyspzhc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpwzxif.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uukwtgyo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqquzinb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvtpfim.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vatsnoxz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rpspksys.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhwbcla.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mnakwxxf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2aihxpgvi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvwwplr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ookcbeqx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdwcyaq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bewcwpsa.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2guerbcal.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2alnsezsp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zuervpim.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrkscia.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2graizmbl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsvjwoe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfkcchn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiexcsbv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfweiep.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkwjlez.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2deiyvoaj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgalrtlv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvqeare.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmntouo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2viasbmpr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tokptfap.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjwuarp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmkkttc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qitzfqwf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oemeobwh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeouvwy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwocuoy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbswjsr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iacpgnkx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2liqnlmeb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqigskah.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcgmfcs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2idemugkt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzvgzdc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkqzjfr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkppvpk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcmmloy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgoqpcf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sopeglmu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2aflhxkuq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtiouyd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2iapeatgb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2erwkyhxz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2eofixqnb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgjqxeh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqcqwxi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgpiqlf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsjxlzn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcqyygs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2effrgeyc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrkpbur.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iywimvwk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zteniznn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2riepukpo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqetrmu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyoreeo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqllopv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdsltmt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxivkbeq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yergjbhf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxewmot.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2opiwvaux.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bifqokpx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhwqcxh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceggckab.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwnctec.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzrdhcr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyvnpen.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqzliei.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2favzmgbh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwzpdgj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwugayx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2itejibqh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rilfqrep.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lifrtkeq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrpfldo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fwglzlah.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoulniax.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uozzgxwf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbzrnjp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xofcxasd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qejoppkf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfgsddo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2obkjgxdt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zscdpecj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhixcyg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnaelox.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlenbxy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2waytfhdk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xsntmkzp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmcpzgx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqzdydn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqupeqo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sncntyxt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2opoimipa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmhdkuu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2iztxwdpl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2daaygxby.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2extkigjh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tuttwofj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfgxakl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxqmxat.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bihjzjjr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2atdklhno.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxjtqdl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2leldptxs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmlnwpm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gayoyltj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlpjarv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqbaboy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmabamq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2phmbxpce.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeslyln.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kbskuwac.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2valmscox.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbcgghv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuhdfyi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2futfywys.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajojrazs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2babrdibc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygywnsrl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgflwuzb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvnfwdh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rveyecgo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ulniukll.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyambsy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qjebcwpi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2itbmxheb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjuqsqs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2etfspxjg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxzpybc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fejijjto.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfkclsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jquythsk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2anrxfopr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wysnywep.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqcunvo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2opwghxcn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcugfag.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fahfvwbe.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaoqxyu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfwrqoq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2frxoudxy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zshdwlxg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dryrurjp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dzurolou.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2skjhqgei.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvoycda.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcrkblw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2whbltlgm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbwbdbd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2umgxamsh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rerjvapx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aejggexw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2unqttlyd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xentngmy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2enavscax.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jivaugyn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nstofqlu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnvptkc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoxouqz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxllyjm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2huvpnjmw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmiscyq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhrwpzs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ilglgnyp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwcuhcp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfgvhuj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgrzdst.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uvozwbgz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwsdyvg.html


<!-- 参考信息 -->