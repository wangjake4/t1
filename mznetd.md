代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjefmcju.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kejsecbx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlkfebk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpxolwx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tibpxutl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2forklstf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsyoctp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cofajvlm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrjgrev.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2igrkupal.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzolbdst.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrklcml.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnptlizj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfgbuhq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgiunmr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwpmxls.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkgncjs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vmefxiue.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkphseca.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgrjvrf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dopflvyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwdczeh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuorrac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzxhdhd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrjqfdg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2omjxemmu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2isfcoicb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ropvzppl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2trqrpngm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkmvjut.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bjesuuug.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ckflqdlv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoxscjw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2siixkrxw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkuxixz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2crhxulie.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjfdaiq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyejyhe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkivfzka.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrtuour.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnavetv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxoqcvm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbquavb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ermeaouj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmnbwoo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdbllkv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2epksjhlw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqlndbb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tascbuvl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidimkqj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxwnixo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsbpbjq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2toedrmsc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkfnwpi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rypbmlds.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2whjbmxbx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbrjml.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoxivoe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdeozzp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyjwnsp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqiyqcl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2irzttkob.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgyrfub.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoueljs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrvrktd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dolwbmsk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rocigqbw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwduylhe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqtziwi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ciddyumt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mqloueqd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtagtddz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwmaanp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzkzyvp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyefhad.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxmoweu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2clekonuj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfkwata.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpjquaq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuykclj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfhjlos.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzldgos.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxusvbm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2opjwwcvc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqfoggl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hfriuhvq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hduerrsu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbashjq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcbxgvv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvahdva.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjhnsxy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tricsrdj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwfgahn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbcburt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbutayo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmufoeyb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvyktyr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rllcmqus.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2faoskrwe.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dysbqiki.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxegqhm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2copwtwvs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpdjwnv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzqvexa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2svwljjui.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfiwiue.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zehujkxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlndhfnm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2medwsreh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkawhpdj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhfvkcw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2edovsvfq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xveizdxq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onpxpsrj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkshint.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpmrnwu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmqzwwi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dhykpjvs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfgttrc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzzurtj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uipuspdw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbqerjg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhnpzky.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvsdplc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhnbywb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gczwxvun.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwvpvnb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxahgxx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwpqkgi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcecypsx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlaojry.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2twcuzhwk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aadywupg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sarppneu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwoomwp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svfzstup.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2obnqhjwg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuumijb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iymzzqfv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nucojhfu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tialjbwk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ribgkggu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2thjprnnn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpszdjh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmbutim.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjhmdxn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvxzhgu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfhwqrr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fzugoylc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgncwtb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqqysnp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcntqhsr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yastince.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkirrygc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzxcllx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzcdrla.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwegaej.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugudesdu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qncnccgi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wffxetjr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2odieajhu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgrpcmy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tisnmcau.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2owboyptf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2djfjstjz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrggptk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2igzmjvzn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmqcomh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fitaovoi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocakaate.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhfcupe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2stvnjhwx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2aokniiqi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbexamv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vegqiepf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kogzstvw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pybcfqne.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnwdxkp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjtydjl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzivxkh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2twaumkhv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpifqoq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2orrapycv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtkxyyd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2huvqlbve.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2egelhsef.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrsjqpf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxufqhmv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdkbxiy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmronixw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2brjzvnuc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjsrmku.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pxivnzdl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rewbvoak.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aruafdjt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhryoco.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvmvxig.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmvuivm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjomrso.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2swalqhmr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bbylncqe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mccyukar.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuhkjpp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2orvbyhjx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igqrwtyv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxvfsnz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lipnruzv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2svfoiymx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ixppnjic.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcmepmy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udxxpxyk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvammxbn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rooniwcx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhthkuy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfuvcff.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfutgeim.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdhfolf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiovlfb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjutbnf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zvntybqv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mvufkuyd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dehtglsc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nslsgcyv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2btvobbwr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2txnufezb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxnwmdq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvjmjik.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vulbhtph.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2docjwxow.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfamirn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2unsaryzs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxdjwpy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdnsuqv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrslqhb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqlfcij.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjhmtno.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2slduggmk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2khgvctoq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqbawzt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2podfxdvy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbifhdbu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgzrnwq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cvndmzkv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2raivxqjc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aeusnqzv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2esstkrpj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2glzcpikq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoirkvp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bmukecse.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuhcgxq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rflxrhea.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfwbahy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2odcvrzbe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpkazhd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfksxtb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llvyrnyl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oenxgjtk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaekzay.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2assiecot.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvsowbt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcpyorx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdxgwaf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvkqbav.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbelqae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnsunkm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zcowrgmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbixaesr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnbtocy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gakiyxxp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqitjat.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrjnryc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ajylnqfr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dykgzfoy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmcmyeu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnbyheo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tggjykip.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjfbqir.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjwcki.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uciiache.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxkzomq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdaptnn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqgyyqt.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fzllsunm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkzmoma.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyvizij.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxyxkea.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxvvoxf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuzfmek.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoucxcj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqpowjw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xxorpclz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwunuwf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tptywbgp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sfihyqex.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tbddifwr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lpocjsya.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkewebe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pfljepdz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrdijra.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oiokjlal.html


<!-- 参考信息 -->