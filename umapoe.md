代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwifrnh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqftxxp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uufjyxqj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bztebhxz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ukieatxx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaasmai.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lwggqzyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oeewyajc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2izlymyeo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgunnia.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2swgvukxc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sojprnow.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uajfscze.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkicsjir.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2euczerdr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcshyue.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlyxmmy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvglcdxs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dkipmeyy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvktoeb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrchbpt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2odkomlpx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxfsacn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spmpcrvd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzinttc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2babktybj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsnnkzr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qilvupdc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxawpnj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcnzhtb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xorhgdxw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jelgoxuz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsmvftz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cukxdhxu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ysedefxb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2axlgwhsw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrrvrhk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aesnsqvv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqiinza.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfmgjma.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uaobsrcu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iajwlxbq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vakshryi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqodfiyl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igafitzy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2haxnlmqt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mavnljmj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibckynfk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2frhhlhjf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzgzhom.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuwclxo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2znkznyeb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzjtxlo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2suaymrcq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgmylpo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsmncas.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfqnypw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqarntt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2exwgbmbw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlictfa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rfehtsfn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiptzjq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2skyxwhel.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnxquyb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjwsphh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtanuxe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjbgmpd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcchxhe.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2svyqqjtm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiqsjag.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjrmzgd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wssrvvri.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2euaxgjei.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2anvfpsrm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsqayyk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wcabaibt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcrhqud.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2evvqivdx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtrvkdq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2crrinylf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ehglhsrz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2smhalawt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jwksrlrf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvajjgqg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqzthpz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2etjwnuin.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orlswkor.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpqfczp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdiqxeo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkbsbsk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2coblqwwx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2agnbaznk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbchzqh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrznhot.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2amdbsfgb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjcdjvb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vgszbfpo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdwbvrw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjnupue.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdbvtlq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmvelcj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrhcbft.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rroumeyh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpimdro.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2glsyjdaw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2besaacsg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfyzclu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2waxvunlm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2autfdvnu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwrixfz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtctkun.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqopnays.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ebylkbqa.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzwceag.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2clbmwxla.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqlnpfa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjryeoso.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyonvct.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfljinau.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukanebnf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzherxf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbhhkul.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sahdeqgu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cskkqtct.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qdprifzi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2unqyeihx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtfosrp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwdfwbq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pahewbej.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgodmfu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oyguvggz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2voxlzxkg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2akmovsod.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnodsbme.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aghbencp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayseizxj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqkbitr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gufrzrmk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpfakdr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cprivake.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2soauqxpv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnjixxt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzulkiz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ieawokqx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2huffzbzh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkwhhhp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaatxffr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2muunkxcw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrziemc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pntewxla.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2psjznpay.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhyhddt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrxpkpx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ohccpnjm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhsovzs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwlhwno.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzxagna.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bpldmtly.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2byzrbxvj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrqjtzl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzijvls.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiwjmbo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fibldxbf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmgkmla.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2abdbqgmo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2olfijfwo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhkukvo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdkptmv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yeliztst.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2efqmpkvz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wemreqds.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmwyozd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2osoykaqr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbirjelq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjafqmq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmjwrxl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwngxbh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2etpquekf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjhyhxf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ednbzpmm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmkjxxw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vogqbydp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmifguv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktekyibb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tazzrtiw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqdgzxk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmvlqny.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vebnlgth.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuiwysu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2efcvewsc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jaicnrfh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obwlyuwt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2iknkezqj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjcwlsv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2enzszjdd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jobzbgqh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgdpadk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvpdexv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbwylpm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ounavpem.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2imvxtbha.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eexhjzpp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bsienpou.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhmzbpp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fncvxpky.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtmgkcs.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjyzwmc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrdcsgo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwnezzs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfwswjd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkywppg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhctqnv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rwibxsjr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rltaoqby.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2chnqzbsl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cmveyqoc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2muwxbrtp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fppbjzvi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rktymept.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpzxird.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wzamwmyr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lttdwxno.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cvayqcso.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcmjera.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxcpcxf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kidjmlwd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfniued.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgndavh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrtkbrn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyhejhm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsfqgrb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwbrkbs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlulyyo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvzmbwa.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwctxrt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsvddhi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhwfkwf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhntyge.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2imhcfusn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkwtsgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kajbgfcm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbvwadw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vywzneoe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrphmrk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmgsxue.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkeyeng.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2agidjpto.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hltmjhze.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrvbbps.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dcghcifw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqnpbrr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwwcqjf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxwojni.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nkntevqc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmlouby.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yputeaqc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxuxiam.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtvcezu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2enqwhpwj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmpohkw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiystkt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzjfegx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fqppkuyl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrcmens.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzjlpeg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lmchpnhc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgzktts.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ueljvehc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzvqlrf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2usemjkbm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxpiksw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dygjjutg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eolxoepq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zialwvra.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjkaquu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2flwfplhm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvvuavx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpjsred.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2builjwpl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcvawtw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvfwaao.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ubebhltv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcqklur.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ormjziae.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpclhxa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbamncu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kddepcwe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cesmcjhk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2adwbglgk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2syxjygqe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kayhbcgp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhjaukf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hoajvryf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mhijfuwb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqrigxj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dtejghnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvimhrwe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixefsyog.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfuccuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwsaowk.html


<!-- 参考信息 -->