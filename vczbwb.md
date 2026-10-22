代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mynjozoj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2abjekjnk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkzhwmv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2stmmokbn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vggdtyfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvulunf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcjxurq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxefyjoi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ujokiemg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iovekefq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2poejqxwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzmdvch.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoyqkzv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pchvuvpe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxlhafu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2anoffwjn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdbwuhk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtnkcfc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xfifanhx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2erorwbid.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mplystke.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnhwhjg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mojwgidz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxswyhjq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jidssaqw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2odjvdugu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kljsxvdh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfewomkc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eeadamud.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgseqqnj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lkucibsi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcqpewd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2znmoxtfs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtutqmlt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aoadzeqv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrosnjgn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxkinpq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcbfmhc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgwiijd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2llpqptac.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbwwzsv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mltjffll.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nfovihpj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhzphsz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2noedexow.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjybytks.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpltrnf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntadcuar.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jftmhevi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xvumeltn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2elneqeow.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhapsec.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nghpigxa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzdjdhv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2djqqefbv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejznofnz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zacxkmlp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fadtadbd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2txxouviq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhajpteb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jfayzmun.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ashdzyel.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fnutlezu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2flaghred.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2idbnzkvd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tifyyktx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pezfqlij.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rewgihoa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2agbpcqin.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aieidqrs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2obbreuqg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqzmrit.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrvreej.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnasilvx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifirqdgw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2emmgvfnc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nthpfjqb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cljpvifs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzejwmba.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2trumbriy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqgjoni.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xnccbokw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdteqtf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmrxroe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiyummz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfenzmgw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiyxlbh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsxphrg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xptslbvt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvhiixj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kuujmbus.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqueoglb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2agvxiypj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsfdfkd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2muhhlaaz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2plibibhq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orxphzkf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaqsamn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2greojfwm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bimeirxy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eghuztpt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dsydfpxo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzfgwsn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdoxxyq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxhaxof.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzihblp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiooeza.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvamocpb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sptedstw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoalqwkn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlltuoto.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvntfjv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mxebmrxp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlxcynv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxqfohu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhleezs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpdoqjw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfhadeb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hktmkxed.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcinybcy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnvwgou.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfwvxww.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbbfhlu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgqijxf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dyswfqlx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrsavhm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yowrncmw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnusvrgk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhsxapd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnkapsx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mookamho.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlaczmb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmijrzu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgzuoeb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrggozs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kygjvawz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bmclsqee.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpqiowo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpfibiv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgjgpou.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aajqelcz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zarhszrk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnxvmvr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvooqasv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2umfnhyal.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsmoazl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxekkryi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngahvyqg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zcklbfhf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlomblfx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhxknat.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzvysmx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvhuiqt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuykuzo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xolcutra.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvqdvpd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mhziqvht.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiksfdc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsrdtka.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbbysrp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoruwye.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdpjlze.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oothwkew.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kcujnozo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2znzkjugt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhbsxvr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqyxdtn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iraswbzf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsdlzdk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyiatwi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2invbmsfa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvihapfx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xigwklem.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtreukx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzbsmqz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxymolz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cxauxpor.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcoqhii.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsnkwin.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvpfcta.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfljsfha.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqemxhcw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2thywnmrj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abdxgkgx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sikdafwa.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjskbvb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gtekqngj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcswyasx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpwvsrl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzhjsfj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcdvvad.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2emouzpuy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjusbefr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hljbyrpo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzezqvp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnembmcn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wbusnfch.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdfqefw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2chearlyw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bunzfliw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfdalbi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaxkxmr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwlacgx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gghapqfy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjtuhnd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dufwejgf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2raqqfaon.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzwiesg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgjpucb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqixyhz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2heohdzpi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbwiluq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgkrvrb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpjpspg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaxfvnu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpxxfmh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xabirdws.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mokzflxq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcnusos.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnjvtuw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcfnely.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyadtln.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2watgslhw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmmpiuj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oplkoent.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwermcam.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2keosidrv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbcknxa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbmfaug.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2omwwbwgo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdrbfcf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzhgvdx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcjqknn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhryearq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfimohrj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2doqiptvw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mszpibam.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2daiokiys.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuuihcm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwzmtgm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oevjshfr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2elazxnab.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kanjgitk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kquhbbpz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jjldtpyx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2knjkqdyi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2srfltipc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbfbbsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smmpvgrh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtvvmaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vitwxmer.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxyxrlk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdtfcan.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ostbebvu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyfwamm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2icselkbu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpcfxyx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyrxpye.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kqemtmnz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkoezvr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vchcvinn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tetmozwj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbkhtbw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvsymmy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cjafxylu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mralkncz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oopikjeo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxegzuu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2svlbvxbh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ehulcata.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zfahdzcj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpfbtaw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdpjehi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2osipckvb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrxfbrh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkcwhvy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2enjbpdki.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2agzlxoqf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxsqrck.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmxwsyl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcozukp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uctezmul.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hstveago.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxvzcml.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjttxwzs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fonfqdhu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzewpvn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvlcnjz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sinfpwvl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2esikmsyo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjeveku.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvxkmku.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxohtds.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpuzzms.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pygfkaak.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nwynyoob.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxtwpym.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jzordjez.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcjlfmz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yfblhhsi.html


<!-- 参考信息 -->