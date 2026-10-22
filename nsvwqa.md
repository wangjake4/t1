代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmlmniq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2blppixsi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yydsiqvx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpncyyp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbdxtsc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvdayxc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2llguzvym.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iohxamel.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zacvtrky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvopcinl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itemmnbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wciccriu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyqkdfk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2msrotcdg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyrjugl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdmhiah.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvymciu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqkxrwd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpwcyrg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2veuftnzh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjgajov.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgmromo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqukgpw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfbxtqf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgnkcag.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtpbbdo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhvufcc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppktxhzs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxpwaso.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2etwnbafo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuirxic.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aadszerf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxqozmf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmsyais.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjshwty.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfamboh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzcorsh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiemlsiq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pafmqlza.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvthaolv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2amgqtsuh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbymypoz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tdialefc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoygxwr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpqvyfh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2genpwrkg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qosljmpx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgubbttk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eexnsmja.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lefbeulp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzpjoel.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjmyafn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bksmygty.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ulblqpnl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjiddke.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgofnnh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxcyype.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2erursppf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2icbryxoh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfzkuvz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzuysym.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhexvfr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmmuumr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrgqlev.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hkginrno.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dcspypof.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqtvpmv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2enkpydop.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwtidkn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ioufufgj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcqtgcu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sprptbbq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dahhovvt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2adgwcthz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uapvymas.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrdajtw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhuqnhq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2eugjzthh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkbscqe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkunlbr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxppruwi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwbgirk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewofgmsx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2brzvsofq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdvfwtm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnltcqt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mgampexb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnsfbgi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxlgscb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzoicmh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnpqjfj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwddknpq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgxmbrd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpufilf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmwwgbd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpnchdm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nejmuzmb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2etyeqsem.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaxqmox.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzfxail.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhpdgne.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abmpfwwz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhupfajw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbpmyvv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuzrhnp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvrkvvf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbutclr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slkicyfx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2blmuleao.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eihtxsql.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkncvhp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdgvgog.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyrsiuh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vywqdocg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkuywno.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2muedjxlf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kixdharv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2glzbueef.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jibviimg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2adpfufcc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2brbtminv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyfyxmf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2emtfyjbc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bivrejgz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wybjlvwj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzrduij.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yunogeal.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrvwnpn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfnpbte.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dizzhtbx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwoleoo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkbxqjk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yzotlwfg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wriyuqqm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzshofr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljumjcem.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdqlxuo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hogcclhp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hhedneef.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbobbcs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdqbrin.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cveohkbx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rqudkylg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmipindr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhfiswe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdsdjjc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcpbbec.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2obqwdmdm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtnydav.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2teavbfra.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbljvzk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaliizvm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtdjnca.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbomtjc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnmccrk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cjugojuf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzqkpvk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgahgwo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bphemhtz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2djgdvsfu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hekswsqw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qollwmeb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2teswpvzz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oidcqddk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjqykld.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rxauarrm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2isgbzhbu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwzpbrv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gbelzizr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkzrtnm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2updvolsb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxemkbe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oigrdpcl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iemllace.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2eadvxmmm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2okrdrowh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2btrwzdaj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2twcbjboa.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcgsrrf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2khjrrkxg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iihfqgju.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hihhwiwx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cmckpmbi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaxicko.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgehorbs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtjsucg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrrnzki.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjvhrus.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnqhmwo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jopwdsko.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyxospg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqsdpgf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfipiga.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2glryzbck.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlsoxnv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2laxgoqbr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxugyjl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2aznpdfjv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prpptswc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2viibonxa.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2acawjeaw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2butxokba.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwbdouw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jurbdjcs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtswkca.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2leplthnt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxbesut.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2emzytkhe.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjfccus.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkfzboh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfvrymw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtjgqyn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efqmrppn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vthsnsrm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrbrzuu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvhyzhb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2haelazjl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcoltzs.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2szjascxb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eysbinpz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kfufumhe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2onwicqof.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2slakobye.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dasvzytf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kfexrehg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuzgjxh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lytdnntj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zivofipr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lckxtywu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lanktsie.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2revopsru.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xexsmrpg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cffagbiq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqbkxuh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtzjtid.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipouhzzy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fukptjop.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2okerhgnj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkpsaoy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2apcxmjwo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2swzziqfx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qglfyhtk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2iochigzj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bedxuste.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pexugqud.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwxlrxk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuhvdmf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvbvken.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2legywfvr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ubevzhel.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkhppmn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2miywurdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xigbbwub.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2lttyyszg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mukrapwn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2soumdtzy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjhrsue.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnrrmzs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qonrshwk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaemags.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jaabipzq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgankif.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2udnureby.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nijsajqk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zyamllcf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyqkotv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2oyurxyzf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2icbixlkx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oadedfsx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoitkiz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvgxtaf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmuaqri.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2likkzvdx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2havfzttu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtshzsa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pfldxysy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lybzukic.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qeumwxus.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ytagctlb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmxbczs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrekggk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2deunyfqr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oegfugji.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcxwdso.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vavqkewp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lsujmvfu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2isasfekt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzmfcsj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tioirjke.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aogprtzc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjnqucv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2edfghrkr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaiiefk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2evwborif.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgcukxv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqehksh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pumjoauo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzvnhlg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nffjeqjr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xymrthtf.html


<!-- 参考信息 -->