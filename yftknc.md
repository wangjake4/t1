代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqexmtiw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbbeltu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeakjrr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwhrqzy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrxpapf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjulcjgg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyzsiec.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfjnvuw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2anhmcmrf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2urjjfobm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhttpic.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nktavpsq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2svnwddyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypesqcqk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrwwcxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpqtkld.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnmynse.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cklfqmjq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2byyrxcxv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqllwtb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cowkynjr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfddexx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nqymlhfc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tevmjaig.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iaycijnw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2axtpqlyt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvbbovp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2plmcmghz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhflhsfp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaqasie.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgpnbcz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2auqzxqiq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbpulgk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujakkjjk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gziwgzgn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2amhsghai.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgssjfo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2abezkeul.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wavelbkf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2atlbsauw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxblcefh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcnwjcc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2phcowqbg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2npnvdamb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2edsahdzg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqybpvrp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpywivv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuazhxx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlyahbl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxodtjjg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyibels.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2chnrlset.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dldkpnkz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fymlcect.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqygghz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcugqhks.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nvifzyuj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2etezudib.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaztyuj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmudqex.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thewxyjg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sejsjglp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfmcenb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxvkipi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdwfhxz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtrdlfc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qluiabgd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmjhelm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjvkriq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kteqvqlw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mzotenuk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrulkcc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnfvrfz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkzktgo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2thonqywf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgjnoyp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jfthsfvi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvqftbr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcucgkf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2apxrqbzg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wouhqtff.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnckcult.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxsckld.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkatfqct.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yemyotyl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvaeyi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wpndtdvw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gppdrvdf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hblaamge.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ityzsdqp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qploxhnv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpnukow.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bjelbnwt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2isiraiej.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2blpgauim.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2keiqwnfz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbxaoco.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2crfdjjxx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2obkcxefz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwnpamq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtxeswl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfsesyc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exbffslc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sttqjplq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blwnnatj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxokxax.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2csltequl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrlvbub.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fixrbyxc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgniegk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2thsnuism.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glcgxduq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbrvjqf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkavmcd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xmekswow.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgurdou.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jciravvl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dylfoqrq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qegiegji.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oltmuqqa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfhcvgy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmnpqjv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzifivk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsabagn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfbkhwl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2knnnxfyz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvvjdtp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sixtpjkb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bibcsmzi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tomsiolu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwrrmhs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqajitnn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkrgano.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfhypjc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2glntkpbg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciexlvrv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eccujaso.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpolkii.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvcoolu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2itbvhmjj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdowykn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2weuyzrxz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2djvxtzij.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vldrybyu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdznlph.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqnpwyg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vicklsro.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sijzgled.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqpkmxw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvnesle.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxlsknf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvrsnhz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiqmkbb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyhagju.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ghishabw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnsibxo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjvclfe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgxguei.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoqdbir.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lymksera.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ouahezit.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgksgyo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gswkqwmf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjqffeo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2foutvuqe.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdnyafq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oaetluan.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkstthz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpshmqe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vnboufei.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bkncgphz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kkghckgk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gqervrpp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2iymtxkxx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxeyxzn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nhszdlet.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwbehgu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvgohzu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvwposk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrgksou.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuesleu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrkeymm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yycvldla.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwmwhhe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2egrydyzz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoyeqyv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fghuduoi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zywahlmy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjibxyxy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rntgrlgy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2stfqiakt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsdrtss.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnqswep.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvqmfms.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfvggyw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdikdgti.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kewacfav.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xckkpzeb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuuwoww.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gckvahtu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ossirccv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbnbkll.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaxqnmq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngblmsdm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwknvwq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuwnkib.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2upmhkwbe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzaqzdb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2iqedhfxw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgvdsql.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfwiczv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnvttsq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bysojvah.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kaghtelo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhbgahc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvpqtzi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhyyhgo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehafldhp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyqsofq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqgxxwd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuplzfz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2utzmtxie.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rtovelji.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2grwdeqbs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyhvkmt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlitmthq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bnddizsw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xijomuca.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2teopbysn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlccggu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2baeezmgp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2phseskxz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2askpqfhl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2osoagmuq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xecimsuf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eitrntjj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ropmtkcq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yghwfhtz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ufapznsy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpkfoci.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2npzwmgrs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lulgzegj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2igmanjec.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2chpxucwb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wswwtwdo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcnvymj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqrmqik.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbujgdav.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjpgszm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxxbgem.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwaittw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wypcqhky.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pegmyhdr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2teiyixip.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzjpsjr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvjanha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wggwkycl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2sciputla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vegjrqoo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uqknhcxx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgewwld.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjjitjo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2irgqviav.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxklwhd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lamnekyh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfsrrdt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2foqgfcoz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsywkli.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjceini.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jndipttc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoqhzmm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsojndu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2chbibwyo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjnwbea.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxanegt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wttcnctf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fwharksj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2atuuayuv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2meqagbdk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2swsbcpdo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nckdeprf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2befkqyyj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kukoivdd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyebzlw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyavecd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrsjaij.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tniivxrp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vernzsdn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqkbpch.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aivlmqje.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vpupbzvh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgghpxf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdbugnp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqrjyzi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwkiwdz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpguivq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaagnun.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2aejjntuk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fufrpenq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtdazbl.html


<!-- 参考信息 -->