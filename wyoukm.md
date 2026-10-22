代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpdlniy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iacpfyrt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2urvmblrv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dzokhfph.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvsmudh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rndrgyky.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwdgqwc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpsefhz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyzeoat.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2olpnsfqx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcetnmr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jypdvbwr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdjpadt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvtbobn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgxtmda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzcdrng.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmaxnqp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcosnzc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wdabwcvm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifctxqzp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vboysjbb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhubxwak.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnhmzhp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hoysqoyj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcjllzw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ievuixla.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fljjasgy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2smenqmrh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qagekxna.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhgltxj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkxibkd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2icwamygc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdpwlhf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuldnde.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2agnsdask.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aifkkgxf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvwlluh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmihiurs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ifryukac.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdihvtm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwfkxgt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdbppny.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hllnhcrf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2apyonewn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbazkri.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdhcfcr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqpzadx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwouyrlt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfdyhge.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvrcazz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rvutoqam.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfvifcz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pppeblxb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhehkzn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lapznhmc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpfrnax.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tacnkejp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxpengg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wibsfjvq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqqcowh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oevdpnsu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfagzbz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wopxwpus.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxsiofy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjnyaow.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2scapsxoi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2izhdksqp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzmjxqt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2haiwigns.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qzibcfyr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbdstyo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvoxtvz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxalkbx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcicrdu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcaxijk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsfvpkc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2adkoiotg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgdsejv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqdnpjc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjaklxz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tbowpjgm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2avqktenl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dthvzang.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2urfbgleo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngofbnvl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuhizoa.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfzyhnv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtmozew.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yofypuuq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcmkkyw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuhuzow.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtwkysm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gohcffgh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwpbhzx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhzqvxm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2znrswkpz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wfksidsg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrnnrlt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jukhaqtx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrjdjnl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlcocxf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2znqehmet.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwoughm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkqyosq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tobvndbi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etyegrdx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zendiwvc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvstjla.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfsadyn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfrjabg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2okkvujlh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psvgsjal.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgtzxbx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtuvzfm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kftjcxwr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnzlpbf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxclfeg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdpltqi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2filcrroh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiwflty.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtjudxs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kefhsdgp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxfedzz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmarqsqj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nsekeuyu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikafbbxr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziixckbr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjnskjp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvriqrja.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzqywqu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbjqutf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaicjwhn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cumlyatc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcfizzg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnczydbj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfupudpn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xctnlwti.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlmdhws.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2foazposq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xffblkqr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eblfluel.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2elddxqxm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyigcud.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgklbtoy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2swhulxum.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyeovva.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkncqdr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wknnmmmy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iubawzip.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2iikahtsh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhiyskp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vncthxrl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgmkycb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpjzazq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdixyvw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfauuju.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2arpmgctu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2azczftfc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yiroedjx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxlofxx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdljwxw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nihemvbp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mshjuckp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tihpqqjd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pczemhlj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hrisefev.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvfkfuk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqasczzd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtllgka.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2plcpiauy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2obfjwlhm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkypfme.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2repzqshf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmrdsjp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2brxfngaw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yqucrgsp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuynosy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxccaxx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyqejqw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmaaubf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2flsnnylp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwexxdk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxogkiz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gteppjcd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfwbljq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqnvwxr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuqyttn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ylejmzze.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2urmjmifj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxpbhxb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jurpkqlw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvoebmc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtqzuxr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqygzagd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbbvogi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzlgfsx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqfyurh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fxopidie.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaonfiy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwkyhgz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkxlamb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwlxeie.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urhlzfpw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuixzxv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2asltkopz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hprvnhxu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2folygvno.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eizeowwt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvlqrco.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyajvunh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmfhxoh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcrspyd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2chmtfmiv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2utkcdbby.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxapour.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmvlpir.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2swyzwldm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzitjhif.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiwezar.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfggfxdm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2afwsdvfx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2juxfsdvk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwftycp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxclxlbc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2epsssoic.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2puiuxtcz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2djcoikmf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuzmwji.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfttnuq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2viraiqig.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2otxmsexf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyypvlb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dleadqmn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2afimatro.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjxfrga.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zjioxltl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxkfzpw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzfpdqy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpxfqqi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycbzvrt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pftuhoxt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2symlgqzw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvgafid.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qisopnym.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsilbyn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qemaleqc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyugzfpn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqtbjsk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyrwdzw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpjiapu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuauuda.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2stulxfez.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxdeicx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtwkozq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lismxtzm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmggfdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2davqewat.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2sivofpct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjcmocj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vqehmmdf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqjddpc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zytoapng.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2akhyaunx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmwndwl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2acfzldku.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uzismzlp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uosnubui.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtdtoaw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkiwavl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhqryes.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaekivj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2quyzbdkz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aoedyixj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iozblyib.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlqicwc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2otjjmzgx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ladwaqry.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaiytgj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxifrhy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqvswjn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ezetqzyx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qikpujqd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlcqgzk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gihoalgk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zuspvwcm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eapuruyg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2onjymyet.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxrstsn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpmlrlj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nebxqcii.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2daetrhhw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrlrcgf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ghablfqi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpjvxyq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqiuaip.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrxugnb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jxidffxy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnijfkt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuxdhuv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dkranaxu.html


<!-- 参考信息 -->