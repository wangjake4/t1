代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmsufdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcpzget.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kabebmdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvytzbyy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fooxnpzb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfouvtu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqvawci.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlqhqhl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyrrhvn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzhdcdv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlhjste.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfnjfkr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2imgjsxwi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2amxsayyb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2akrpftac.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmumzzpe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhggwwd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfxvgzs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbgqofx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyaumde.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mehvdzoa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2utuwaptq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tsodkvqp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiirynf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gsajzezq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tydlsseu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfnjpbw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2deruirzl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcajjaew.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfqcrlc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhbtzmu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpewyhro.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pvztvmao.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtnexln.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyhewlp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2csfcehqe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejroqawl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlukzzoh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mfasloix.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwchloua.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lpislmsg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpyrenh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqoymkm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvanbwpx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlwnyma.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvnxcwy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbkxtsl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpikzyz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npnuzurx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjcbxvc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcdvefu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrekiez.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2axjhxvwh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcadhfi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2srqigjrh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjhaijf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vekahefc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2isnkxgba.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zntjluqo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hihehlgr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkpqtym.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwxhiiy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mefqrfrq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2elqkaqxb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrrfihd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyeteiv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqvzqeo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdmvidh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqqyxve.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkuefhn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tsicgthi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjslwilx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sarbueom.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkvcgxc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xsignhpe.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaohxtfe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2imukvlgq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2txlmdpsh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwoldvi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyyvmlc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdjeckb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2erlxjbfa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xytxtstc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twubpeah.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrfohjw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cpubhzce.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdbmndb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxchhpl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qzefegsf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiuqxxo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vddkbqmv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2evspzrno.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxuyqpe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txumjuda.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxayikp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxuggsw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjdciqh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhrrstc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqhkaxc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbvgyao.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2arpxhqed.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfoxrzn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uopjosiu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uazbmlpa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2owzvhote.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2audbspqu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgagspev.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnrurvg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iorqvrfv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqldfyrt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtygrqt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfflkdn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xrafmruk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2abyrtqfu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jejqsidy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lypgwupf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfxdvhg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imgluraq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrmbrvg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjjnkec.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeivchv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlofktx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkqmkxd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpfehxn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdfkfna.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsvatdq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eaerqlna.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hequtkyu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdertyn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwznnpjo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwbxdww.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaytuvt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rsksaoib.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejtztmt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2voveinbk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cayqjhvs.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cfznihdu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaynaqc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmekjdaw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfldyat.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lzybilyx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfahdug.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdtcowa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbbczcl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnpyjdo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtbfprg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwstjaa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqietix.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkoskhh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzmcpyr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2blmnnjmu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlslxqtv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2alcxmhkd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuimxkg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2woqfjplx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfdfktk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgygbvq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2aueinmnx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlmjaib.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tcelnjob.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxwfvtg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlmskob.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlwmgwr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrawrle.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2whokovqa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkepujv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbxctum.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnouiqzf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxfqmgg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuhobho.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtyshiq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2twzfvemn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nwntervv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2abbbtlyq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sctegtrz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyukcas.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2slefhkek.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrtcurn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hptabiid.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjeedmx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2obvxdmgk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oofteyev.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cruafioz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwtxryg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfnoxad.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlgqftz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yiorvtbf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcevxncm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmljwva.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsdbcjg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvyctgx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwpthim.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xjubbrbh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwfcrgh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whsvgrsu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjdaskt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdrfrsu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcsdflv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2solefaci.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hygrhejm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yirrkvwk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dlllxgtb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdfnmwq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmutneg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2psrcbzjy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2inbuvxli.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpasmfh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2emfpbcnq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvdomrl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpegdlgv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgvqkxn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvsnclm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2obskkolv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2espotyng.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmalsnf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nyimrplb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xycrzyod.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdytnyms.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtzrcho.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wmilurap.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmmkerb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxprfqw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2isriibit.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjsgug.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrudcyq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfedeenj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfgelnl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqggwovg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vmerpuvl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhatyosw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2epuzuihi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2srcokwnc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxvvqzl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyaijuk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqyrbtr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfppitpj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcrytae.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2exvxblvr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ligblsff.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2azwqrgcb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2thkfqhar.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaqmkkn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmejwhqi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcsaxsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfpmgyy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jllnqmjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shfsqfmb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwfwqz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2viyxntfu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgbjglh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyqlmlz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2exwlxffr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrxpdrj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcoockm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jwujnlef.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvmthdw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzygcyi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zdttmlyb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dujhbtbn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfjlsxe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ybllsrsx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eakazpbo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoqfpzf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oappmxxy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdpwars.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdqdtiz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqndsgv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zamdhxsp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpwdlez.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aroeonad.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcvnzqq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kvonuzar.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbatjvj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iskctmhl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2upvipoul.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpmhzfs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcrbchl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2puklwrpr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2anprcyud.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ffciwdnc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoszged.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sesncaqj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhbvqkf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qabqklwr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbjaren.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2frjlymew.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oazucxgg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoyzkzm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzirxnt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnnoyye.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyxvmzd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dyycemtp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxwsbmc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vawvgclu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2umgeegwf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qihhqlkl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xqghvndg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqgizmm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkhuurb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhuoaoo.html


<!-- 参考信息 -->