代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2syshzszl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aoogmclc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2auhxwtkn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrzbetk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2exelqmbt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fuewfbwl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwqapox.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yijyvyix.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2thnvtmqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzwncah.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhyuaqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrcqgey.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2orfgtgqv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfelgbn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zviaojwn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgvvlfu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpudfxo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbwuktu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvpolrp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2heaclkuj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bztdexdt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2babfozst.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgzcbkp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfagzfmo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnxrkao.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjtdxml.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdndnxf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2owdpxita.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2egbtbqtm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2okxlemii.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cluffkzj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vteleucv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvvhkpr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bywoxhks.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ehledqfa.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oofdblef.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqntqxwu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzrzkng.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2imftaqam.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2imtyxnuf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvsckxl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxtkqdk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wabbdhbb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eglcvmgr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2prexwyei.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2azikhivl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkpdcff.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeranxxm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vuomyltj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxakroab.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkfmlhb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqswpdse.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbtyoul.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2izopcfjj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cputtjdg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjnlsgi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snealcgn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvvupki.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuhsrhj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevzugcw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2inggqsve.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfobpnn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpaxrez.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jifldavk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgxlnre.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoqhfbk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jhitvght.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhegfmg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fksnkmgn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nsffnbmn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vljwjxdr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdacuoxs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2obdegwbk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pwemcmwm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgvjjuz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfaopsv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2igmzhbeo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvntrepm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2juskxssw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmsuznq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vydaaeqj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgcvsko.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrhcvng.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qznfyuzz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2twcggapw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqqxwgg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2smfyfmej.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuzpypp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nsatbfbt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cngqufdn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbwmiqb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptosuhvy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2btkshiau.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2exhhddpg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dezoghgq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjuqwhf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rykcmhyg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fweepuou.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfflxxx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbcysns.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jokngaqo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkirijh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaddvko.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2elwaiola.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fynnkahs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2oarkeojs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xekubnou.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2equtomtp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vncbkfsn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhsigdw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qspzwinq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gegnggrb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2daytsmrs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuljindq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mheloyqj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iznlzbjg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxnahss.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfysqtv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2etmubuyh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaqknkt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bivlfjws.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bahnspqd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jimjiocz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvcqfnq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lozpivms.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcfjlew.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vscunmow.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbuxdhz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbawfoa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aatsguby.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2riuwlcjd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtkliji.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2poctlgwc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzmhxor.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2esjgqtxj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrhednq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbgcnxy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgwhukj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzbjsdp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkallirr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkemcro.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcynsunw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2idlxwqpm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsgftdf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoutjjh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsshsccx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2skcyyvjz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtpdrwf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmhikrd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdrsjll.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwksqpbr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2onikodjv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbjupfi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2umbyhfkn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2crugvavu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfzzikg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gkantaiq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2boeqoecn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rybmssge.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtiwenu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtdtpee.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wlenhzgz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uezuxruy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyxshbi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuswizm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgqhlyh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nunqikgz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsstezw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zquecedc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuqswlm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nuutwqvv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdhmtjx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbwbrdl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwkinxm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pxosbdbl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszcfhfb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2whssfhpf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtapwdcb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2crhnanwa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmtmssp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hobtgxly.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ksikpxiw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aimfyebo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwwcdlt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqbyoab.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmduhwpo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vgofbqyl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2csfflebk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rowmxddq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsnxxgn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdebezx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msnuhbmj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbgaugb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyzeioq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2csfsnzli.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgevirqg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2notgzpkx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2joznpxsi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yybjtgaa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lybztdch.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqpkzsj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xclaumvo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgcnjky.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqajhocs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2atmquttt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zggnvrsr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyolobm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhaqius.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cotokifm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kcetcrwk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbqqdpn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuocqphy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2amwyhskd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2snlgiiva.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkkqknk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvrdley.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhynuli.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmtxhhw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdxymhp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2helgrzhl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjslmvm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpdcbix.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2emgcotag.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2txbjsoej.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oreltakc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiwhjcx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mimrvcty.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwterds.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuzccye.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwrzbpd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2txuzgbrf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfgqono.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjhymhs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekktdrfc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhdhcpm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhixbacj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqpamlg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mguniopb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xwttpuez.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxozhja.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpfeput.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ianckfob.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiwxbgj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnooryab.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2htbirmao.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzfisdg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uimqzize.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfaeuzr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoexzwv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gvibxhsu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxotubs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxfvryg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kinwpfkv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwtoaio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmmsfay.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxkmmsr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vjouocpa.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kctlirlw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxmoggg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ewordbik.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kintosrt.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ycajtdps.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvqmnml.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lemvomcw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yubxbejs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kabtlfbh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2npyaojfm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cskaxqyv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2woglaauv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ibptbrna.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2laoubdmi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hitsksoo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2atevmjsn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qulhsofe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiyjrod.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2isfntpqp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrwabbj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzfkcwi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2neqrrngy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtrrzya.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2drhylqiw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnotwwm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzhoyem.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2osjdichx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hxptfdwa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdqykpy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqsbqkf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uigtlwki.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bncjmxsq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2idrlqxrn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuyzspg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xghuwhxr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrnjbkx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2syfakbct.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eeseohif.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfzjcwl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcmways.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwelqd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2acuakxza.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyvcoth.html


<!-- 参考信息 -->