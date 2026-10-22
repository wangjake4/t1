代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sycjdpgn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnofypi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2czoepqkq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2etsrpmhb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmdenql.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsomfjs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinbjouw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2siaxmlmi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pelxzbqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knjtphzp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhwefxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osylmdxf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kljjgvvh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvkdeop.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjjoriw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdzujbk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kbozebgc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxgspqn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2brdcjcgj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaiffof.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtyyzbx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hebwxgne.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fgldrrij.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2aatbtvfz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xcobbpwd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yztitlaf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbqgixw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfghtclm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsypkqu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrzciut.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaerruz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsldormj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yldhdzlb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgkblde.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2feupiprr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnwxylq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2npxkhdfd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yviudvwm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fajdthso.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrneryi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdzrerq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqozjdn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjusspt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpselzv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pipstknj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzdsagn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsrxxcf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvovfqnk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hexuymzg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnkkqxt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yovfsuzf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxunfuk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvxofhf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2chpooskk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxsjego.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2itakmujw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhqordf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oywqvygu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jjirpjsy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdozdhym.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yuojazpr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdxgvdb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxofmuv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vngghbqd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2owmggwko.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qotvbvwn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mdarcees.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tagzxfou.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2owgkabvm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpmmzew.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kflqvluz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzrsaaq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2axygyrio.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fsshswkg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdercef.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgvgqoq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kagmglnk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwhzbcb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkdzacj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbeohmt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2aetkfbns.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2creljnzg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmchomoj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmglrkiv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dzklpsqz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqikfig.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcqvebx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjslcit.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtlmhdw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrinxay.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2snbsqhdd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqwtych.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtrlcto.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbfyvbh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuzrwfg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2duprbqon.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsxjbne.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2veszcfdp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2detxlwac.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbecbui.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjgyzym.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eueybont.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfnokdc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kchlbtrt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmatsmm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbugbbt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqmxxah.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuycdrnt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lobtntxa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2buyudldh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvienvv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jreqgcpc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmjzhfj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajswcmye.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rurlwcir.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaajhvcb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyswfgw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbnqgkg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hzprstbp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwpurso.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2inkoharb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2niehglqh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2demzhlsg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luywnmjn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2khmnfnhl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvcbnse.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfdrdqz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mutgcgcq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrbxali.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2indeichi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zojahowt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnysgoy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bspelcvx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kidxrops.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbuzjab.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2utafmhrv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjegsnx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtrldth.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2edrygnnv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpualyqw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhlwfkn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdglmxnt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvhuazf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wktwrbpo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhfnbzm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvncaamo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dklyiqgz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2djjlfpwk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbmoegh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbjwokm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmqnvoo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qpezspir.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2txkjixnj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxtrgcg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpjysmw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfqrbtx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gsydrtjv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzmmlfr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxofdamx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuqwzpm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzqoqyw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkjdpfj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzyviot.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2flphznvz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2apvpbwqp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2esgmsnen.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gthqfqzt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuqtliw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2klbugqhr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bknciiuy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxkqpga.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiqvjom.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhsniuw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyshwfk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2srhdsukf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjumvgt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wuykumop.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rauwjinz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqldaoq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2scugawad.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2twtvlcdi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2njxsooxo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgublwd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mprqtxjy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvzjexm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bryinojf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2catwkjrs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnukfmny.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2opgyfssg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yplquprv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmgumwt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czesipft.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbpbtmv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2iazohoiy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tizyjqym.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpbznro.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaprqio.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqvekzd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgurygi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvseasmx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tsioxhel.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwzlqkq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeiruvj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrhnziu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lephjied.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgglnuu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgsujer.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jevwxoub.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kmroxaba.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvxwnds.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqrvuhu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xayvmajs.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtifuyn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfocczi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwqvfet.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsobtkfs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jopvvhkv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxudqbgw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2evluyftz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofskwotb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoeehpu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxnhjxl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxabbyw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rxybechy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2efoxquzv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxmcczj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wprcinsf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvqxmyt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2crjvmcna.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnnygne.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2reqpvcbs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lclxejel.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzovllcq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2koophdhr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgewnro.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfcpzal.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhbcsdn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcwcttw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zingxxlm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2klcaitow.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrwvuwj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiejnts.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2eblblnnu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyvhglu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrmgtmv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2muwkwxvx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nanjjroh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkfmdwo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvkogcp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iagvcxao.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtriias.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zktftkiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2larkbwlr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uexyuaus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quvgijva.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pukskjsi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sojrfhxk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmrfkkq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aedlzfsc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uwezftrj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2arnaeebi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lbculkom.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxuxsvr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bllttgtd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rbasbema.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hhismbyo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxrwwwi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xbehosfg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyivbfj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2whijgvuk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvdpfnk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbfjmmk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjfwzsn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dgovdmlp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfsrntc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxanrdo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkhyyzz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hwelabho.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoqoyul.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2songaftj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqtvmnc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrraznv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2svttsmak.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dprkvrmd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gexpamit.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2whrvvhea.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2owboqocc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhmxdph.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2srxcjwol.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2appznnwz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2viehiedj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xknkagbd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2aktdseyd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gctqhabh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzwlsqx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzpelja.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2olkmfskb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlfyvlo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsjnqhw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyzurfi.html


<!-- 参考信息 -->