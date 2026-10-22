代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kqruhzuj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrjdazg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wznjaxxs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fnczaxjh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kedzwdem.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfoopub.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grjudckk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cibhcpoq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzgurmv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhombmw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwyqrbo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnrqjwy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xldpyzph.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bmssstqi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjtfonv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dntdtkna.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdrlmrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgsyyxn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kauddzco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukabdwef.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqxexua.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkwkbha.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aoswlhpm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvykmqh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jonpfytr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgjuurg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkqmzpf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2icpfcwmp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2drlaxoxr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuwqysa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqsdizx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuopjqrv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vznrxdgs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2esfnywxc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2owupiqeo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgfdleb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnazkek.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfnaxvu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2opgekams.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzvwmdg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bugxrkjd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qphfzqpb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtlnckj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuabsuvv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2erevgxwf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nruirgql.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaexqwx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgtfomd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjdazxy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvfhgip.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2odtsotki.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiqfymw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qwynogdu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqtsdsf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgdboeg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmcvvvc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqduazd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzklupoy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vrakktnz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgmjofu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbzbazy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2swllasbd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhaxyis.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwhescv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnacikfp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnscxlp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfuxahh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvgjxau.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2msrhxywd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcisdzqj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2okmxprdo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmwgfiw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zonadktd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jxormxrb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qklcedkh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kliygeww.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lekljduv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqwakir.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2srvpwikr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpcpkns.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kgecudrd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kegvqcjo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hqccdzhs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhhckst.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzajeym.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhqaaap.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqzrxsu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtwzvtq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxflvku.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbwsyqh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgamvigi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwphagv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuyeeya.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fdosybwu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfnvlyv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqfqkps.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmpjsel.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzthcotw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtrxqtp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iekooymh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzgsgar.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfertqd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rieqzcdb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoyasgj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpqfuzk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmrukbp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylndtxtr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2znducizl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hudyyjnw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfllvawd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2haxwfsuz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzoujmd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2czsitjll.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdtdiki.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibczmttv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpjwwpf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqrryrg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yjktsdma.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wplhhayi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqruzup.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeluhob.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmvsdqm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2teyonipk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfdzcwu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2slzrsymm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlfsbpc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsbfcim.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzmnkyc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrxzqko.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xylgflxl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2brxztggs.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sywgzbzn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bddrbcii.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydndinac.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrgckxu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2srckxrwa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hienuowo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqywtavo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqbwzch.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vndkqosq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjtygdw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2efwpdcwg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ablscawk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiabxswb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnoqgym.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnwftkh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eofiaqlx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhearbbg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtynftw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2preufqnw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2odtsmwsv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzdghwa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvjqzhz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfunsnbv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mscawxyu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubseaobl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2swqnbdxt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzqissh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swokicgt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuyyqgk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjabsbq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfgddov.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbnyszh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrpjibq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hktemaes.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsnwijc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azwhvsyt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrujjos.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvtjxme.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2njraodmh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2crdrlsde.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2raktrqmu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rbztnopu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpqvhci.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwnujnr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ifihajhj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkszjsn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wuerdzmr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ooghsynp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsbgykw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbsetvf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qkznmlnp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kuopsluy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zealosjr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoxumhp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvtefsm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoyhdcn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzzowdi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2akcqobwl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2amcbqaeb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rorpkxny.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2oemlkifp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2emedmixt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyzeerp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sadoanhc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixreaimh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrtjaao.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fruhrjtn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2enhkhsxr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2femzngyd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyjwbyq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrttsvn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vysyqhyh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgiuqmy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jeziauun.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2idexkcfh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npbbkuhh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2luyqbiob.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2imkmixaj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qynhjiae.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2esrurlcs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapqqivg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vinhhtow.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxecawga.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsnklrv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeipukz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdlceba.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2otaahzjq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzomouik.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkdesdo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtfoazs.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtrbylm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeiebzx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyhwpml.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xukuxndn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfxevgr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xmztflge.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cahkknyr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yygyykiu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2spomjwvk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdxwvja.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbokigp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2emwjdbim.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2evzcrmvh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyetshs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wnklpzqo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gehkrqme.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2irawqyha.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dacukcll.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vzosmbzq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xktgkxjd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2extcmceu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyawugt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2trpynmow.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2naeooikk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwehaogo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvdycdf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxjqlai.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwohtzk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2evnyxkcp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofprwkwb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qknwwxos.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzmxouh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeafcom.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzjnroa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbgwaye.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvenpzt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2trhvfbcy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvggpowy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uitaxewx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atbycspv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnotejj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shvfjrwt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gejpvixp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yehgbvuz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uovvggfk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2arbxlvry.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmldawf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2edzauynr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdaxcao.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuxocsy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpdhwvg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmtdkzi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdovfel.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtqeyaw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2unfyxmew.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sgovfoly.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxpaxbs.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2suaachwq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kslcgmwg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iuejbqur.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zcohqnwq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoyltno.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcgbqdy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtohilj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlovbmi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cofjtkxf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nismhvqu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ulduwfec.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2icafxwbe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvoanij.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qhayitde.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjxnhgj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sezgwnqf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vhehcwgv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrqydvo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uejuxhlx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmwqusa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrhsqeh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwvyyeq.html


<!-- 参考信息 -->