代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlxqtsx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hebzybqi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpkiwzb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ohivkpdd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjruvbio.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyzncsg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtpjytr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2atzrffkt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygddhdyz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sxggcgze.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjikfyik.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sibybowc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeereql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyprgtr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kklcmwvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqftgwe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzeidbj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhzglkp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sydcjnmy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvpswqo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlyfdng.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqcucdq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ceezbnbl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdubyxp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvybbggl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hivodgdm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2trgcnoma.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqleeii.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yazclgph.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyydbpi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2erzxzvnl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmgpvrl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vavilsby.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2miiuncsb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tulyqbak.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpspcvh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaevuvt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnpavys.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrocrmq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrmzcuz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjvkumc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmflynj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmprbsy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2veuecfjd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gezohvpi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pppvriqx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kcghzzek.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ampjwesu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qoolwivi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfcossk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2modbzkvb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuftffqp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dzadheur.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcdeopd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hijjbgzg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyvuuyy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbiiejf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxauxpu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlikpnx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2szoimvsv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaepggbu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kudteoqr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2awduxufp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhejlzse.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlxehem.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoybdwa.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2huriysnt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiefeque.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vvretbew.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2exsqskqi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lswhmseu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yszswwhp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnjeiex.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2knehhnnb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyihtiq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2daezdftm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2eunxvaqm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyssvnh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbgfvva.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzwfajc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yslovtlm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqxoldr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jixtbgrj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzdsple.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lesekhap.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitzcpfa.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zifyvuns.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcjmfvi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sasobtfx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzxphql.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nibkcrjg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2blwmbhph.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ejibjwca.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhbjhaq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxzxevu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtlchbm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uothqlss.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfgcjko.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdvhhhm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xidygvue.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pundtboo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbwlkdc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgakwcaf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdrrmaw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avwdtbmt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfzxety.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uopzfbve.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rsokfqff.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkoktwa.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwcjkef.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxqzavl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcmooch.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcjbvsi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjmexwp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bwquzrpe.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhlpjun.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2htjcchxw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxxlvfi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeawhjj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2loavouiz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrxaqgi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzfifov.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lulznnst.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnlkmui.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgongqv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2knwklfuc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeefywzg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sanxysdt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xthgxqir.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efjvjhaj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmnxlol.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcnxrhj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzelgnst.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhstywm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2neqjzpeg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhynkgce.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiedprr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbstjwto.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jakgraiq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2monfhdbb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2meldajhq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrkzoyo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxamawi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwgetsp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2exjcryww.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhvagzw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xplcuqjj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmxqvyi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2focmlsah.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqpcrxm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sorkcjac.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2faesacid.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2thjrlqms.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vifyhbyn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wldsybcr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uhonexok.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2obfucgaa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjeynrt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odcstfbg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ixniephz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xabmmyfp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2flqkvuop.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vudlxrvw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rogdkqzy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzgwrpg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zkglwyhu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlfkkpt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2drqfcpry.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iwivemhk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kufthizy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2luktzvfz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mjazxfqc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbuekdo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsnlkoa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmtatbs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kvclmedh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ecibwsve.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zowczccd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzmqltn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzxfopk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxrmfuc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2grajbgjh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcylzzm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mplvvmfz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfelhbd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlsykoj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qudqvudn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2onjcijsi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcwlpms.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2grtigqub.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jfihddzu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aszrjpao.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2utrhhayb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwpxfaw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2luejhcrw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wudzymqu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2whsmgyxg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fstznywz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhynyxb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlnakbk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tihbqrkx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rpysfywe.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anqbmypc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzchajoz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lxafvzrb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nyprqfjv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxiodnn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoprxrui.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nmslkymt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeaubgg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uvidxjii.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtpwnms.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2htoyiaxo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2txevbtff.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svofwclv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaktqndt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ggisaybt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmnacyf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqvzfbu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2iahxbgmv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lebuydyn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrysrsvx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxjoglq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2keyhexry.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2igqbqcxd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnikpybd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rndnvrwh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrdggbl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vielwohq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2frykfeni.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsizkal.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2adhtwflr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeqajnb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tofwllsv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iagdbmpk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2llvdpkfv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eetkriqr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkwanzg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2guezuskm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2remrynqo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlfacyq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaxcvck.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoqrqow.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scfmaafm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2npbmhkqv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aggwzdwg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwmsove.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrfexpc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yiorqqin.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2adxeljqv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lebhcixk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2diwcomur.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jppwwgqc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqqjbyk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaobulv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yugmxige.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvuclnn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2slbqjarj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2damwjtas.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fknrqwsy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2arsceusu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnikhzx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrjnugd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjlyzct.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kynjvdax.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgfzywx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcoqwan.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2khplnnsu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2trdwcdye.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnwxzwq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2weuzxxio.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwntemg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bghoskws.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2weppsopf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yutnyxjt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wsappanf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2woujirbe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2czdcmcgn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jtipriib.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qwljaaov.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdiqeoa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tplrcbdm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxqyfql.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqjhcxn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmvyswd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rtolgvik.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mairhkht.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2chmwskdp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2frnrlvpq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lkinismb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uyciryhr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpxljhv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlbyvx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bteayyqo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpcmxzq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ahljymuc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jaskouou.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2whvhwxdg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgqdmmr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ycigvegw.html


<!-- 参考信息 -->