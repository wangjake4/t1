代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2liysgspi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofchsepk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txceqjoa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfygboz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuabldb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvdxfub.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzozzocl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dngpogxn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bomihgfm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjlsjem.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhswstx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgdffht.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxlltxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wenxsqji.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyrjpul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxrxzig.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2frcaostb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpryxti.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yovcoibp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ataptumd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vicbyiko.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfhjmmn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhfazyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxkxphg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kfooxkiy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbfqwea.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwapfhq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2znnozfqj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukssppre.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbptovrl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmfolsw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccswoijs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmwrlip.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyazosf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhrhnyg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbptiv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuzblcy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmkbhab.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2devrhjdq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlhlpxh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2msdnbwsm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjumrpz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcujlfog.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzveqdk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nthzcimk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsadgym.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nsorhxfs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyeswru.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xnazzphw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tccxtepm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwmtjhs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlpgomk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lahyaqbh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcnksyw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2grxlhcnd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdpgnbf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpwvlsc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xezxvsmu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeohjln.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrvafrk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrocakj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2scwkvesv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rliehpve.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2udibdhkr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2orfytkme.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2theukzvu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlafxrj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnkwfzu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fdepyiqt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdytcdl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpybuuy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrrlyqf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoccnpm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrbwxoo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xnljmwgs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzocifd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iogtujxd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zaofiewv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmgucbl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tpffdvfs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2izzqpamu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnifdtxk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2drrxtttk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkuxbvz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rweuggfq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzacwgef.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbnxckk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiqovpv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jfplmjsf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wgccxnwf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vapbtuwe.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkdwayu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dokkvcjc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwugvon.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cafzkwvl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuulkwbq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwpphia.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfwvdmb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2adcqntcc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iukxcvox.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jitxabok.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnojpyxr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwklese.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbnjepp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoimckxq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyosnlur.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owhasdsn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwnwcjr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgpfgpc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rytbplzm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrhicfj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqttsyu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqvzyyn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dbepvylp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rclphvlv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xajzltbx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfqozcb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqcrbmp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlplqobj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjregsoz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2khiwbuei.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rezymmbo.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2viuhuaad.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2chgpxbow.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kerfvjlf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvcuvrq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwchoexu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apvskpza.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2huuhjgtn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrefbni.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnrlrkq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hngltsfp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqywmayg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfualso.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxzmtfj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwfozvx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrtaemw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoemxuqs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zesbstxv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzblfmpg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2howzhzzy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgtefeb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzfwkrc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdmmgba.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tiomecnt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqxcept.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmomprk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcjkfcg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtbhukv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2voblniim.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mybxuivs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgdwgpv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2brmehhpu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdqsfw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmycwtom.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tswbwlki.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2evpbregk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtaongo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyuodnb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcsebvm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvrdvmw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhatyep.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqmikqj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgszafe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2myxttlnm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xztvmlfo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vczlzcqb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaqthip.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2favlzsqx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2djoichhu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ulndvnos.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrigwue.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pttemtgk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2suasqada.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gppdfual.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvwlfii.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzxavjx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgcalcp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhyzcdm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkctwaeb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrbclpi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlasqpw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkjyjkm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsohmhwr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hpteiwnr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2izkwyzka.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fchzzatw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjdjdqr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kukrozjz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhsynah.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hitvvgwi.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nexrokec.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rytipdpd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmllztwi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2glcwfguu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqgbxex.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxysmrt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxdmjuq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cofyuujt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdhumxt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwjhzgo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpozpdr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxbvhud.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkomymla.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhokjgp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2osdgjdxr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqserpy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqszbrk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2iawjlolh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxhzrod.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjbxphv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2opzkmxrq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvobsgh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjfeomx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dargyihs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2txvtvzsl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zudkrnwa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjnxiot.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvcqwfv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqmtwue.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiifndj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrvvbuz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iitidgqf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzdfgpc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpwuyqr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gixikyje.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hklljasp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xitwplqf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2czrtcafo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqoohpi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yigantgb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrnalfe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtixklq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qorsuith.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjyses.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oyclmeoa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhohwduq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2otmsggnf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2opxynydb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxersfr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aafxcbix.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfiljfb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zctzmyxf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvrrars.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ucezmzwx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2awycuyrw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmbjpdl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxtxatl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdibwsn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmvvcam.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2miakkcqg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2shpqteve.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2olqoklaz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2llxndrxn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqhtopi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzrkvsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzqynwq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjbgqoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psodnppf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmyexoe.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zworzxzx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2okorygiz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uailehys.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpmnwyb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2okfceqem.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzgymlz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wejsfgqy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ehacgsof.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zblutvav.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmotqjb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtovsgx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrgfsmj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpshvhm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpglriw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqbtgqb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnnjjiw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrmutna.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jewedgxv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwsmixw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfxlqlp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkiiinf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgqgvvt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrrgdjc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wggpjqqv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jpljswyr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hajombjs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wxccqjkh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxgnngk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjqpdxp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ofltqnsz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjvhnja.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wompocae.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjsmpf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhzgdvf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnojdlt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2blijbtmn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnlbqzu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwyfism.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nueekfij.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lesnwgtq.html


<!-- 参考信息 -->