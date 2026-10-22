代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qalnadpo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2srypfhgv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmmroak.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2situxynp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzigycfq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwshben.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmonsdo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2potkcvuu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2twmoxwfd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zthpckdu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfhghcp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zukempgz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qsayvflr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qetkilge.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zejkeqpg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaslgsz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxezavue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylunaxeu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdusiaoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nulqwwlv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2labwmguo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cilbdfvu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aeinuyig.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqqxbxg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hslywmwj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmearcl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ljposggt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mvswvkev.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2itdltdtg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcbyliw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqifudn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oftdkpxn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtqlqoq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2snqrlfdd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbvkxfl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdizluul.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uulxftka.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ismjmtiu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdvsgvi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2olnppdnz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2unsddsjk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwukufw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2deneqxok.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzejkdmm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uegphani.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvtinat.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuxwpes.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajynfwoh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnhtwcf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyczcyg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xmowpfdh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrdktzo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jqelmevi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jruooryc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xuftorwk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkimxxyn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxzywft.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2csbhasxf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kioystdk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrvuhuc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbegpxx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2briuyfmu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ycitgrhc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfnvqfy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwefnkm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zqixsyhp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2puzclowj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmfxggh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqcdtck.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkirctj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yoolugbx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2grvjcnzv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcrklmr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sctytass.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxpryos.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gmixkmnu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbmhkaj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzkybze.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhlldhy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2upxepomi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlmjtng.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwbkaxk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uklfovra.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxzuixf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hibkillb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2stuxduve.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eygtbbpl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hafauizs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2baxvmnof.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkhoevd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsosbhf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2egaahuom.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnjwbie.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tepynrrp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2guwagjqh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2phmaxucl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrqrmwd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dipzryfa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kutsbpvz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgosiplp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjszzsv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hovkrevj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2trfwaikb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaqjodf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkuevqg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qredfgrh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxldcihf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwlpbmc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vovqgcdo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aamvcrye.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzroxflh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qggndvdg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyipznd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pkszjazc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mkupiqyn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glwsejnr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2irozgeun.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uhihzxqe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bqticpte.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjaljge.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xutyxmsg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyndzpsc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdojrhnq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yypvyqke.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdsxtye.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzupnkb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pogbbmid.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxahixj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkjoknk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2iumsjron.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvkkkws.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2elxwpnso.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2loutxayp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpyarku.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbyxifk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbhjdhy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmkbzsu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqkcoyi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2phwvmvoj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxqathu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2phnzwaxr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmayqrcr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqirpxr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2peqqdljk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkqvreb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2grvtktcg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2siobhdyy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwrlvqd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2budovpxu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnofjrhf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kufsteyq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2txvrmnlv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iseqnbwa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnrfxms.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjowybm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsinvpm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxpuwvl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtxbuvh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zyolhyjr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjebmnx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjggprq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcginqua.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxxwdjc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bqettegl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zyheytmu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzumqfqg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krxgorae.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2opxirufq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzucrwe.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzaecoa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkwawbw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2akxdjwld.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlimwdd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2guvqzzmr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2moripnvs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2awhinpgg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtslhcl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xauiltyr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqxtnum.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmvlhqx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlgwgiu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnosmqe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrbddnq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecomfnpn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjjaxok.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cigmxesu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bddlhgwp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxcxotv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bmanfdvx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsaacww.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxahbpm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnvfwvg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnemwdv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tntodaov.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiioazj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaceotn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfckxoh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwynrmm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hztyftnj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoylboc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iphamgjg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2alahnnrb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2moqgnnsz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nktqhqcd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuhjavb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dirxcbnd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdbqine.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygawuwwi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaxiqvz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oafgibdj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtltyas.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzhozef.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hserjlwh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2egmyfgxj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdyxcva.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2liwqzofs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjicmye.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iczjqqsk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eifolrqx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfsbscr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nazppalh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2crrafxtg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbbauoq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuynxjd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqzyoht.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrdbxuy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2eaocawzh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvikxwo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ymonodqm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cplwmvek.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lntayrfn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wllqnrtz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cuskqtad.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xudqgtuj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2owxjpauf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oajmepmv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhotjjy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2frjrkaux.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2utplouuu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgkciqj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaleetd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqebfnq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2agqmfyrq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbcrcrs.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvvdiox.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeapyoxo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdyhczv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiuzqme.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdcfhpf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzacdsgn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tleatclp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auekkmoj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wgejlxka.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsinhww.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzrjwlu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nsquvhla.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuwbgdn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mrumwvqd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrqjboy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjzxvwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfmfkad.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxpjzzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycygfdkd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yheqjuip.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqjaitw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfkjnrs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bifjeyaw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmzvotk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tyciwcaz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvzmbwi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2crxjskpq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cznmsszo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjweqsy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfuwneq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2itwtcvld.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rambvhrv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvqvnmv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmjjhrd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2itwuscwt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2phgxeisf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtqgqun.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvvkypr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2znnxrevu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2eyndgana.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwewwnp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lkduupgd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeiijjr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcddmjz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uynbtsnm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnziazc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrvwnyw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2afsygjjp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbudoma.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkevgee.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2leoaredb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svlvaala.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2atepvcwc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkwjoio.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrqsdmd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwxifge.html


<!-- 参考信息 -->