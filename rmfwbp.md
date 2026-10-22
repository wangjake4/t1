代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcaxffz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyfuzfu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqbxjft.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2glvmdydx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tulmfkoy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oeueezcx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pftlhxip.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qmckxbvm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ranrmisp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjgjxpr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvggbsyx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uxykmjwo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2buqzcjjg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2intxmbiy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuydptsf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgtrnbg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpidjes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dynnrine.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuceintw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knwnfqbu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsupwhf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fasnfskn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvacykep.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlktkxbz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjqracf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnclbmoa.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2abionkth.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qisqpsln.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fgozlpge.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhpbhqa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgjbibn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkfrdbx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2flrzhsib.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bswuxgsi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqbluow.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyyxrns.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2icindkjd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdlwelv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwxybrs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwnhlzy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdfidpx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnugyjz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnugzzr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrnmfmt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krtbkjvd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2orizgtbd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqpawgk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufasjmfr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2szbrebqg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2aspcnoyo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2avxwwvtg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2usnlheol.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkugrdr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfvfwss.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcrcmxt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jysbfdvp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2baegnxhk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlztjur.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqdpqim.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymebgknm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wzypggau.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tchgpmgv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmgmbiy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2enuvskty.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuhlzlb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlfegto.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twsljwno.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qumjagoq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ofripgkn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwlbucd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuzspgv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjyeqzm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbrtuiy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpviqfh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xposjzoj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjntbzb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eduourdn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwhrrpe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxkulbb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zugertah.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2atayqimu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2muldvznv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcfphds.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzxbsun.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuqirqi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2afbwwaiw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdwhynm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2akthwnfw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzooonm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgglckq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpkzzcr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyhyvij.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfdanyk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2spsjkqfc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2laaxdntv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvyhsln.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gxccndkm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsnihzc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvsyhoe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2keeaxtet.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2omsxmddv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fcryrxfs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgvjyfr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvafvhz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zkulqmst.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecizazhu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2floxqkrq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kexazvws.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucssrrjm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lijnyiqa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwgnwfr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2iqspouri.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bljdmgzw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gcozxvho.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrawhep.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgbymkg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pviukqyi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uenfbhrc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxcfciz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbfxwps.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jlctuyfd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nprrrjyx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prkdsjis.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoztypop.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2anzrzbhq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uulriaoc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrmoxee.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaafuha.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxmaarj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2onbuubyw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfrgszx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oksziwaj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrszjpkf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knatmsso.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uexbxtuq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzyflhv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2txgemgek.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmsqfxg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2implhuxb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwoisgt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jtscsinw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyryyieq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkokjkz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbdgijc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmpcamq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2afkclxla.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ughjnvfi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpalcrel.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnpxffb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwdfjiv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wazmdcdn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dskdxmei.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyuijzh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvznbcro.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpunngx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2smatvhxd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnkhipx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eauhmpaj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwgmakq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaazhrx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whkvbzhh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfnhiop.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwvvbto.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rhouafbg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkljuam.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmiqopj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzscmhk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlbjmwj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ychdzsxf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmedmcs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2syxupluw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2etzwvbxu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vasejzjb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzvgeyb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qodcjyet.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfqysdd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgnyxeo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jscrklrw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bxphpecm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjxabua.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2istvlwym.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hycimjts.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rnswdhak.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqzwjak.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jebwrdjx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwnrtck.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlhiqyq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qizjhjhb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qidtruhc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sktfpthf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuxvlza.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqxkzm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgnzkbi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifltqoa.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbphsmn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzemdjs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yexwkjih.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tktduxfo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhgixrf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfkjdpn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyfeanz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwlyjwh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyauxoe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mublwhnb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jinkgkhb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2akbftzxv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkshzgrv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlhytcr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lfazshlz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mylentfh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cwazvvxl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcivgbrm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsxkzdx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwirlmg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2auxtukgn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjecncvi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vetsqmjo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrbixmg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeaylkk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkevxag.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpvrcyr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uscscmab.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2toogfbbn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvalxzza.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jyisdvna.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oivsfvie.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbgkbpm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcjjtdk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgmtnhm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlsvvvn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdnwli.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2urkhjlua.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqsscdz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcxiskf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2esmanqrm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ersmkpwn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qshoevmm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyddfblt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyaaupy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnpkugg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cfodyoll.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zocivkks.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2boqpbmhw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkfabmi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2stjtegsi.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjyuokf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dproogud.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rapwecie.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtqwlxq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcizzloe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2amvmwdek.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjoelnb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtpwiui.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jmowgmlw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eedidary.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2izyrgazk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2slcrbtvb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tleihyjp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2omcawxnu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyeshab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nufzzqvn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aszvjlak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhlmeal.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfogudp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2slmvlrbb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdtazic.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqidhuy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zikphjjj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ceimudnd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jltnbiim.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrazucv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kadwdwlo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jjplgage.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsvvztd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2upgdjaqc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ueguowuf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eoamkrol.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjjkbpz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwmlgmh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoiqnof.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxvgiav.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2engakvku.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwbzwcu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zayrrkyc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2adppbqem.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fzygsghh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2betgtedf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzhwwgf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzrqavx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2suebgsfc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpbshel.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaqxdbm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2baucmvqp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlivizd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rlszipsu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2queequpb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhuyyfb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjvbala.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcvselj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lhviysta.html


<!-- 参考信息 -->