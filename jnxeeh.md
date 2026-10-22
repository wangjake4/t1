代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlmbryt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnboakn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgcfyyn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwwyqpa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hskjrgoj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iymuvxat.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ergkweds.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuvxont.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cinazjfe.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vizfyoal.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udcephcc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxvqitz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvxwijp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jxljkmiq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgpzzpo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjxhrbg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpwphuc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yetdyfeu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqnblki.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yuryvaea.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gephhnnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwfhpqa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agvzmcis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mueslroh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbfgtml.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2whahrhyb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vysvozaf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zseowder.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxukuog.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuylouh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfnasjd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdcuutk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqpommk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyxuvbx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfpgjjt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xncbbshh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyiuxbl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nooptgwe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2grkoelso.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmefswfz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dfihkwtl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuthcamx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbtgdfy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlomlxt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoxopba.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlrhxhy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qncxldfz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzrrcrj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivubhmmi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmotlem.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwddixjj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vawlrtfp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2eumptwam.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbekmwy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnxfdxd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdwevop.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qugqyqzs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnenxwib.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wchnzxna.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgaiqpx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oozqjuoh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlkahpd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxdouor.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyysvfom.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cjymnefq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fezgjdnl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkfbgdw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zadvzlvg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhadnhtv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2exejlzyc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eeryarbu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eflspueo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2snkrucet.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rltbgiin.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2opwpjnln.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfphttmc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ipswbkae.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hguorhjs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2edknexgg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrztrml.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ersuxunz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2weizqdzn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcplajm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlpinas.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmgrcbc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2odsiozdb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bzefmlsn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcocknh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiziuqz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yszcvrer.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtxmefe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bslqkubt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlguxmmo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dejeclwq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpekavl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqqgjaf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rshheczs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vmykevcj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2johsosbi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfehync.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlldquf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2egdbpcha.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhmqugp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chplihxj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnwowso.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wxadidzd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lushdhgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wglmdyxh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2skgsrvge.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejweajbo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2monrbbay.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsstwwim.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvtnyit.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmiqpfb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfzpxjb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2otocbeyg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyhscas.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rhihkoqa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwdoeuk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcvsxrm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqtyljj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kliplzts.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qagfxhzd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcanxtme.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgzvyaj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyfpepi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmfdnur.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxbuscs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2omhwoqhe.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uaviqdul.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xraoknio.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnehpvx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaeddnz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbynangs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpztsby.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwrbtbh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbqrflo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yomoxwye.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bajamgnj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkzxauv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtbzggl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaegwvty.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mznqwjpi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2motkntst.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kkutaxeo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqguvzw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2afsigczq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwymolqt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hblqhmrf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lomaejam.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqpiflm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2igsvgovh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfwwdgm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrzkgxa.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgpdqdt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihenczp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfqlxum.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2socwbuwy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kssfyhsh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbctevxw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoeaixh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvzjnwf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwngrftu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrattsg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpeljic.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aybbptdr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvbkivy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdnrody.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ooperqvb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oueyrnsz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yghjhmfp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzwdnzo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qttvklji.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxmwrnx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtciieh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzlctzz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlvdtnn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mxikadxd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2plcuqkhg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrzvpad.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeaoqgl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsqjhcj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyiiutw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqauojb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpgulri.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjippgs.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mikporyx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxodarn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjegcse.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2idilxgfg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmuxpde.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrwrrru.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxnrzff.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uynrvaos.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqiflzf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlnybxh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeiqciw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsxkndn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jblpshqn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvpdrcm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxoovgt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnyvbgt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpgnsqx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oacrfjon.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdyjnxn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bdywvhgm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqewjxb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvsbbhz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzljphpv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2akeyztng.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blgjbmfs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zozjmzbt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmjnjgs.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sipbtouv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2znhepmvj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsnatbg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvfmatr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vctxijbf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfyegyy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fodrzpts.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wffhulop.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmljokjm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgxloxd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiozkrlk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2haxilety.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2heoublov.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlqowik.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoimkzl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eylsqfjg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqodhqd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcukatg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2niyrzuyo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkgnwsm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzkeckv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nlidjqrz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dduhskwj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ucikuyxe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqnfajf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fetznyve.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2htruewgd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tujszytg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnffweiz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaqcznc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xucwnaon.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zzezjnen.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbfysgd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgpczja.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjcxnpm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nupqpaok.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhrwvod.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2duprnhct.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cafeoyqd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2spnfpews.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kirfyxjl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbqvcgb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnowdybt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nupwxyvo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2htvrtdsz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2imhjgywh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyqhfzd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2abzozofk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qnszgnlf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsulfeql.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ruheozun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyqccqt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cusblqyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wieggulv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkgcdzj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhvruml.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvdxmef.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yowniqyq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqptaiz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmezfxe.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eajrwkqs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzrcrbk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ipotlmpb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2onjcdjpf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnpynos.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnzwqir.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjbdubo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yzudunmk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2shmocrcz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qsamgphm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrqufwz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iqidlaqx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jusxtvkr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gprlvqid.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzjkfur.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqcynqj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2peolrhoz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdjmhdh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaucjgo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbbbecj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mqikthjo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jupwwuix.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrrywja.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeijvof.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtzhixx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pygbiwdk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmfnzts.html


<!-- 参考信息 -->