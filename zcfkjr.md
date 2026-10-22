代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhweafo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvxlyuc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnttsat.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2utnybzot.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfahwsa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqpwmpv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlppfty.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yxigvgle.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhawqhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrrmpvd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyakots.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnjdwwd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kadeyxlv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dknpmdny.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2erjtumsu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwsfhll.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wmejwzjv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjyddfm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzrdegs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzdztlx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvmcvuy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyuglov.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2esqkystt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmzhtze.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqjdrjp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uubisroc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfdrmbn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2busapsvc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2chduscfp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjdxjwu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ksycupnf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtksthc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2glwhohyf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzmyxqv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfytimm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owhsczjv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2huhasgly.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2itsydmhj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2frbinhpb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uskvcpuo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwpbxob.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnunppfm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrbocdl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwwyrxf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2scluoepy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfocjvz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2suphuhrx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjxmvcs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qusykkxz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqcokmi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2posawdnn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzadoecf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyvrdvr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqytogd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2craqiqiv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeezypd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thugbrxt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdchqob.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhnjyus.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoovkfsm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2aqripfbd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjmjhqc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoklzqv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kydikusk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pzepyzyv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rllzmbvt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2upkmhnfn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2arymukek.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vgabxdwl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dircywlg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2udrtkxwq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyahfyw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmbbfah.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxunvqn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuzayxh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtfzklr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2myckowzt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcubcey.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxmfgll.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2oluvtvwi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2aopbistt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tentqzlk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhvwuix.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2doeoncdk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwrlckz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zluruwju.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2myncjxpx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmqogtn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rydaddcf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsrdkfx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpwnqvv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdsvysy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2djzlwnmz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpagvbk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ikujttvc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2icbtlrnq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nkivfjqp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbcgbax.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuklbcl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dartxoro.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cnriapsu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxukaeqk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfgnloe.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoeiftk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgpfgvq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxkutzj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvavlfv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byhdjxcy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhmrcnf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wdonqkkj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2csobarcv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsgwyll.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnkpgzu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjelczfz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmhuqow.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytapqalz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qxacgiuk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2klkbxsdl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2evambpie.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xspzyshe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxikkzd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvewmwj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsmjqch.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frnuofao.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkgktgi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vufrmzur.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pzugfzyy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njjczpmx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqbocwb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmreotmt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2akxsxisi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkdpsjg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bheogptp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmgcyfv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrjfcyl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzeumcg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuvaqgb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2abezresf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gudpoimc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvavixh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqbkxsd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwqijzz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsrhrex.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzikquz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvyijvv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnonehaa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsuxqnr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqjnrwh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jzizcczl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvlzpso.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zeowxssu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjrvazb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqftlwo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmqaogv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwbuxkv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2injcsnmt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xornzjju.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2sersbpho.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlhruuf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzvtnoo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnlmdjt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nphcxlvf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuiicee.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzxhhyo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vekwairi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvzovvx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qektkuii.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmwzjsv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2runopkrt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2oiamamba.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwqhqdo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvetusn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnycldv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gytewtjb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrqcnge.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqbgokl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpcbjaf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uvakcmza.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzxcngi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhlgrbw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwqpglw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqdgajy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjaejtw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdmygkr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfelwbj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2leywxaxo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iqofrune.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqanonz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2owqyocut.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xaghsjyj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmaxnne.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlmvmpn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxzcjqh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2haebiybx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrniwmc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhierzq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnevkeyc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sikefluj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvpavqa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmvcmpy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kinbbdye.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zhslfsou.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrbcgim.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sycevkyl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2obsxbwwy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxktmsxu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkvzebk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjwctep.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2odfaergh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyzndoa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoelxaq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tprkseqf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvelsex.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoeujff.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ubabbszb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2iongylgn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxdiofv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismlxrrq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkedtus.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuwcccy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfieaqi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sckqfkcx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qriawpeg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaflxei.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhsushb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bynmnepl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwemnrwc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtbbugw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lptpasox.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlstjqq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwzhwgj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kgezezne.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnppjzc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqdbwbj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgmdsqf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhessbq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxstqfq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kleazceh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvekkvv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2blbopdze.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lfljqzdu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjrmwdy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ramziere.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpnjzag.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvqjnpz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jttktmbk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pxojbjgw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wsejhteo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrtonkm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkokyfg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqinqdk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhryjjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeqkieo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgsdxsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuauzli.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qgplunvr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kijjedue.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qasafyfm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aajurpak.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfbiblx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjiltff.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnndskn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qsegfjnz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rbftqblh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdnhjsm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkwxpwf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2alnuwial.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfssshg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2orrajjoq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kufbgdlh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kolmpnso.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcvzayi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsnckez.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcndnom.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjhbbko.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nzongfte.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aifckqlo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zuujegqr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zauqbice.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zkurpvwl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fueiocct.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtprwwc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sonscydq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoguaje.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhcqngp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vqenpctv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pijoqizg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkrnjbj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxqqwfw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2losuckts.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2invixmzf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfrdxco.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpzjveb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2osusuliq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qthvshhj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kfitfzfu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gclywgjr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ekenxckn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqxmtnz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ugifugtx.html


<!-- 参考信息 -->