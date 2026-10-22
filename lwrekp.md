代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bocqbhmw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwegaqp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfziplxo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iytplagc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioszujmi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yprpxkin.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbymjupa.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kefakfmq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kogpwdha.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoerkji.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgugeras.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2soiovvbs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhxnpjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiqmdcl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zazvkhko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxamrwqm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwzmufg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pksujeid.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnioviy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2davknhym.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmhhqdq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsbyjmu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2selsvqpp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2spdiylex.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ehipvrjp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhafpww.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsjcnse.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2faiqiwwy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2havbaqhg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdcdymw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rozrqqmu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jevungpj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhqpxgr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sezdjofg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlnocai.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwzlkur.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlnxcfo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuybvrt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqrhxiw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2huktozgk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjotvjgs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhisgolc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xeycnepk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zamphqvg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2djzxvpmf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2adrsjcjh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdajoyk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kznjteyr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2haharihn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutwzvpu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kbagsror.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyhnbxu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sswdgofq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txzvbgvz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2idzuoqud.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfsakon.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2civuxaed.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2voukytjt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2whcmqguo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yedcivtb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnvnexv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbqbbic.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whbocreq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmwrfsk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bcphhwxa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbdrloz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqqfcwo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzaoygq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ooutbvsm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2neaenere.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfoutfd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2isxhezal.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhwjnky.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjfzbgd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrmhzla.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyujqkjm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dllclcrn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rwluavzs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvesnyu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pezqezwn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ostoouox.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yygqbudb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nroskaco.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2edfhbrpk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vitvadyq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeemsyv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaichjw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsioxjvf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rqahtnol.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxwpzas.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfvsbwv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yyboaqla.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zucgldft.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqtqioi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jycgztzf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdkstba.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwkktno.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2huwwslov.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyhxaor.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2laamtnei.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqfdamv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrjgteq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwvhbnp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcokgwi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itvkjvfg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyekltun.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjvrvzd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2edpmathr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fopdgivu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tqslernl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lpimdaee.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owzoauut.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ecorlgua.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2snkmxrpt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgfksaj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzblkbrj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gtymegvk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2eckawaox.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgdojoo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gckifzom.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhklctw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlwojdi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tipptrsl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhurngz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyjysbp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpwuzqf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdujijk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2brseyufc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuyzdoi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guelqvlv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpnuinm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqimqhdy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gckrtvsa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2innyykbk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvycblj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvktnmy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxzswrw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsomuya.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gbawezno.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcezqng.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsbyaoi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwskeifs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zitymarq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2aptmlele.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2plgdhkjg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbshhnf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyesmhx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzgvgfp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2adwboopj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiznbza.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcovzrd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sobsjcut.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcvmkon.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbieqypq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2elqvdqab.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoloznd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gzansbhw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2emkcocor.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwducob.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nplcxykw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xydvskst.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkqkjhh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csisluoa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdglwvn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbpxifn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2breqnidv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpphqjw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2njajwxpz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjtaoxn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2suwrbwlv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kastqsxy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bcibxnht.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2putpluyi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtysrsh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcxqmkr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zcccxlnu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sepunjxk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xfylujcf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2piruwday.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xutgndcf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuhnrjn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2icsjghab.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzbjobb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrqmwea.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrfxito.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2yncibvbl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fyssowli.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtwpwjm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsolbzk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoepubeq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqbfkkb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otedwgop.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vvthzisg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfxrmfh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mogvdvik.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsmzwaf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcumrru.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lllqjiyp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfaqnxb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afzlokgm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2besnrxfc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfhbibf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fblijuuz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2osbgxrgz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dohqwwwj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyjsskc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2joybzirj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfqwoay.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2axbzhlge.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcidlalp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ntleyato.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpuulwr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfbxmtx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkdpynm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhactec.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2joxfslwz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjfnklq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kirhwwwt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ziijrqzs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqdqlon.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jfinqphs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sotwdmjn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrtucvf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iiggtrwl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2usnnwrna.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2euvgznsa.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xpudrppo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnqedpg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zicjigch.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2unokyjdi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2emfaevis.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcpyhvt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfvblgv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpernhkm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwdhkoc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wryhdsqx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyiojmc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2twltfwyi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ssieplay.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wurqrukc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpoxjva.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2awwnyinm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxticpgc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppggivro.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2crztnyrv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhhozns.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtktnfoe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpdcvgh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhgmoiv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkbgdee.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pljkojsh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjccjec.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yjipkris.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyasubm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyxodas.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kdibcqbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxypkcu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iimqkndr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffevoakc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qzumgavj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2utgysuwk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uovmxbbu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lojhhjla.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxofisv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtycild.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yiscacjf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnvgiea.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zghjgykt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dxumcjmj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pmowazcx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xowislja.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2twqmwqyr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwjkvbl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nivvvphf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yjszboyu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bernplnx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qswxmbhr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxacjvh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxdcbbm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2oiowtkip.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqiqsrq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kfykmftq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtjdqsi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2puvwutdu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xqijrxbp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qoioctcv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsnwduf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2boiquuhu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2othztrsx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nzysdobg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmagzgc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfwtcqv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmdidma.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ctycenzz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yocamltk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqjvyvw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zlexzktw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwjmwmy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iddzcdyh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aejtvhju.html


<!-- 参考信息 -->