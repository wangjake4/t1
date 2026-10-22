代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gecsmdlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbparec.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igxfjbol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwpfaen.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2azfyyrvy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jeehjqxz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2etrsakff.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wamsqoqn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2upvcjohs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntckfflz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ustymcxv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhfkiti.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rrznzwhn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwfxdyq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcajmif.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbncsha.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lthzbmze.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpdxibv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwwqhce.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2olpslrts.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kuicjmml.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mocrjtyg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgrshqo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqnraow.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hylsonix.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfxkqon.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwuqwdh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmiwgfv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnqicnu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyvddbr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrszoyz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2owmudbxn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ousaavng.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dspximde.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdjnwtk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgjpxnk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnvaguq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lglpiggl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2licstpyu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zppcqvvt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaneaiv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkriksw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ofezbonc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwxmmdf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mmirenvd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2uihfiaqn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sheekodv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyirrlhe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vczpevdf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ubepfmpf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnmkawx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jayjfpzo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mphyxpdq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiyocfs.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2higefaxb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2agcjpeon.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nydfybws.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nessfnkm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oixhukeu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zetsmmmb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2odoenscf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fprjeaic.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fkinxqmc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgvnpcm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kagqzyfx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagvmop.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbjlxhq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sexmxvlo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2znoniibw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2odkmmvaa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mqddnawk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfzksov.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2prgmddad.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevxzprx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vydwljbm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kegrkcqy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnjpyxh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbnbvdy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ecofbsot.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkanver.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gojnmmff.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkozsdra.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzxvhzp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsxiknr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqinycc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2weuvytik.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uymaittb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2krlguyqu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmzupek.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrmdhmk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omgrgfic.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkbcsjq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wigjpwbz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwugftzg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxjvdmk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvcibye.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aszvhlqe.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2daybldjz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyssdbj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nywzlyxr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tctlqjcr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwatrmf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpyqnyy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyosdod.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdbqpmm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdrjxsw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxuzgmi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqtzbtp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2smmjucwk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlasisg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zkawuduf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmrsftj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qqblxhzz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2grfqfobt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oehxezbu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvgnezm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2emmofaql.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbjmltx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zylyfkja.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrbwglz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvurups.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fstsyabc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2faiqanza.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqgwoui.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrnpoji.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlibwvvx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vibbngwc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyhcxke.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2epxdearw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgwdbxm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwusahw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuksvbk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kadnismf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqcmrhd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yosnruud.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlqqnnd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsnzqqx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2psyjnmyy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2peszucke.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdljukk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dowvumpe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2odrkjuvc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlofahf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlnynqa.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pakkbdgg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kinifijo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rbufilgo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2brhtsqiz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqyrdkc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrixqrku.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2losvlsfr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2juzetfbc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjvujgz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlqryum.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzavmfi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvswgvki.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqvtmmf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bpedqrlu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhotouu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxaliff.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2imlygkqb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hycmgycr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2scplwctj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2glxwyhoh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2smvstgqe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2sioocvjz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdzhvbe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwagpnq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbjauqa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xspmatfg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmcckps.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpuwafz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2czsqhran.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlzhiys.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aznjjfjn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jguvszqu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxotayoe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsddxqz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qgklnost.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqmlbik.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kiokxslw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmhdttb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phacwfry.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msficjfx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oidyrzwo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ghixdssd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dwopalhl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2furlqopm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwprwguw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kscjpyxk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxivloyy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfofcay.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2neaqcqsf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yayqeehr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrlkibr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxeyyuj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sppowzdf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpednxso.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2losacmfh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fgansdbp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jzafufev.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2trkgkyxc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2purxsajn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgmvyxn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2svvcypft.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2swzyqypv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xsanikyp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkaxmfu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfqxagc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmujkwfi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwomoyh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ienggliv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbssktr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdafeiw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hznhqist.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2znzwzlsg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2evozcqps.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiyxkmk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkodqqq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2slhxusen.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2audtrxdo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfotwcqs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cmywzkop.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwaqnnt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kwukugzl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqnwzof.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yslvreig.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkalovno.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pqemzwqc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uotnscxk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlswxyx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxomivuw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2poaywmnf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmncmkh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtdwyvr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azvbtacb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfkxbuj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnjqpuz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjirjfg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fxukaojg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2daqeojzj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vydwzynd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzmjnoh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkxtqvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiberzg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvntuac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tibghcgf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dvflyhds.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwaxrdo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vieexgvq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2czxafzda.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdsqdnd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkbyysx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eklvvkyh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhqezxh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxewrrw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzycrjt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpuyyvz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sryllmkg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2quexevnd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ncowckha.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hvngtumv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vvptcvem.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cpedsarj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmkjmaz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wytgqend.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdhicsm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2aimjzuzv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2deyrsrbf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pbietciy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyayfcm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vrykxosa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jllkuycd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvxwrqk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hahdidlc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2agufioxw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2utvpsqmk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eeykbkzv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiwzqxy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpdcivq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfeqkmw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxamyzw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhwseoy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvsbcoi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2eimmywqh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2uedcgbef.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwaeacj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkbeghn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvymsrc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pkseaiwn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ysakuxim.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2atzvdhqv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2djymmtwg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mngzmsbh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjckfpcv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxaxhok.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kblydxzs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2afksrcrn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyvgibp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2eythtjel.html


<!-- 参考信息 -->