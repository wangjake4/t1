代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkzfcsn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2klupnpqp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yphqcnjn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqgrqit.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjnycxw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aodacsbs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2osnzykdn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkuumbg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcstmpot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2katiabug.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkshazj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfijdcj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zicnrpff.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qlradoqb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhioryy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqeochh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2klkhnoqf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dldoxrqw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cezkviak.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dlruzhnj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2riixgkph.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkawmlwq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zszhjrrh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2papgtaxf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kudttjmv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nivfllvg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwehzaw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpujhxj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qdapbxin.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hczgijbf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeewxnm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdusizln.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjwwnho.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwwptqp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tetidcmw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rllibnud.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jehvffhf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjsxdng.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnoztml.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsgcpzq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2szejqaoe.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxwazoo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfepqxt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpborjhv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vffctlat.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vveqvgtp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rizaxvyp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2geijjgvn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkhcmsq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2afvszjcs.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbnexhp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkccugea.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjsmnbe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvvrecy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2noqhhpfz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sokkoeej.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzgyryf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdvtakx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2muxptmna.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2asuigiim.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mzycgkba.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2suuyyufd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ugknhkfj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaiqkeu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2svpyjqrd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2woiqhrho.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbxlgaj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2atwfeili.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2anvmenja.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eufxabug.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsmnfnu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2orezjfnp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmmlbnu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjhdvvg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lupavocm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lopukvjo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qoswlrnc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvwqwaq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2meixtsba.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nareibrf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbgrhpo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2msefibul.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qeowmosd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkctepjy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nkarhxfn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2egpoftza.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hghunctf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ibecjfgj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ozadmydd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgcnhax.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqjzgsm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkmuheu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xyryvbhj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ywloebvw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2texmlwba.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kigaxadj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpsvjsm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2umqkaegk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbdbntt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2frisriao.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxybwpn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhgflvi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2easxshuq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mxorltth.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxspcttc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxwejcw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkbpnwu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsouvdoj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eupxzhmk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcvfyhn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcqtzlh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awiwyyuw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhihzol.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yquvthuq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tperuncd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tozgdrqi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ksizhuhx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjujtww.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmyndqg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrloyvus.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ihboxmut.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmchtxt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2skfuvxid.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wncvopya.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaozfln.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edkwbxvy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzrmcbl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uujuppgi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrbnkqq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hivlbrsq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2coaoxwto.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqwvcob.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ntctpgvz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnqghau.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcrtraq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeiapxl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjatjie.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2goraifhx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnbyobd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmssfcq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlpznun.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgercqfo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtkrzgp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zscvxvoi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnvwcar.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2grccikzh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovrlkw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rocfgpob.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwuubah.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnmursc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkpctul.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixekdemh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcomdoh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxrvmmw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhjlktm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2exhylbjo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuundmb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkpkgwf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeudvve.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2epvdklap.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxdpcwj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uunkwdjz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hhobrfit.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvmommn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mnljqowl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvahzgm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2plpjeijw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2thbwbckj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrhjzgj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dgadkozs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rcllqhyh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2npbtmzms.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbalzgx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2psjtgrss.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2twhmfajd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjummim.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxadxlj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2siyvyfpz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxjbmqw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkoipuh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrhkwhs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qpakljmu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hikpmfuk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxuqvgq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bheumgpx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbzbtyt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnntnzo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2talvzaup.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbpayyq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvfihmp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpkaegw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cszeqytb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdijiug.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2trezlfmh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrlhocg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwgmclw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2istnlclp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmibfls.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqbbcfa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgckmje.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdccwad.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hggvvrmw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2otixsvip.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtzsuxo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ttejkhvz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcioepd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwcsyfg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oabvajrv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvzzsrk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lbokazcc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2albshnfq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2opmvuxyh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2azravkey.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qixdwgos.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjjyqem.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrzfpfk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdplsji.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrdbcck.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bkytsvgh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gicciygl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zlglxydo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhkzsaq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qgidmvbo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2txpidhbi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlxtibq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtovazwc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ektatsel.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrnnetb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lsximswt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpwmhtp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mxparwep.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqixcxp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qczpptry.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhrvdnz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2htqyfute.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwffznsc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ckswiouw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkbkbha.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjvppta.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhzfeku.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvfvtgr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhnxnmg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxyncbv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdjsadz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nhplxxpr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxolwbf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtfokrk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmpypvv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2domxoddo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkmqptf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2orzdmslk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2idwonuum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrcqfxw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpxyhgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgwacxt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdocyrf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dmogixwb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgjldmk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2svxwdeat.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqysbdh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpfkcfe.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oofjngco.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoszjxc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuypcnz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmbacyz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2engyvuee.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmswpbg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlgdgpg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqkiksv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwkwwjh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oipfusno.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2npysgfai.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaiknod.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeopnli.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeapuoo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqiarie.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsybbdd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eeawklii.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jxacovsh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bgglpdvn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzaxffj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2msqotvtx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2apnllmxv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtsbywy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2axdgtfug.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoadcxo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2foqsoqlz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbbtfbq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vymekhax.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhbuahg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqfivwp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2megbgnqc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rhguccnb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdspmku.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cotqyllu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdfyouz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hulmmdvv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hedzvcwc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgnqtml.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsquzox.html


<!-- 参考信息 -->