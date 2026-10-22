代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uonfjycn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeanpbh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqreomh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbfcflg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2itsqhugq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyubpnbx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxferot.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rofdbdjx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxsxdmv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otxtbscp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjczeeev.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ittoaopp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhrbkvi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzfptuw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pckuvilo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiixyso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdxsvfq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utyuortc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uevnnvye.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydanvzsm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blfmcqvn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fulepajl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrxaqkl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyvombh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dadvynsb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyplnam.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrwimes.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bneihktk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2auoyzguj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2brdhihej.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2delxekey.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbakojr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrftkdu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2isviiccu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jellmcno.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyxzapj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfdgpkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnwqdmj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaajzkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoxfmhk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yjshwfni.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhcdzbf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuejiqg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlziuoqh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaivlkh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2btijxltm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsamoyz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2idtwyije.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2azloodrh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlosfsle.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvsoouz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxidgjgp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdveutc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceagppuo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmslsxk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hknrlzsx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkpvidd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mscerjfj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2prlpymcc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeydnlz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhhmdms.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utpzqsav.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qxanpyzc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcbcnaj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2actfkjrs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdcclus.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxgftwb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfdcklz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uiynpetp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyzhdkb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yecwhfgb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaznfqe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjqapkw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzdtkta.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkqzeeg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2imzorcar.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcncznb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eziwzklb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhgfowr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrnlvns.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2njyyargg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjtpoiz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhglkvo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqarrxyv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiovrtw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmtedws.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpvtdma.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqzyesy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2snmyrjuy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2olykscjc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hupjkpox.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zayhwllk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrdalda.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hetsmyjm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2emhfijnm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2iluldzxr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qyotqwia.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjlauzk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wygkysjh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ethavleb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2okmruytt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmlqqzs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzrqhmy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jtenvjqz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2baygdwfe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fprqbzis.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsizizs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxioael.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oijlytqi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pphbwstj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgwzvig.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oupxhewz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2skilxvba.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qcklwych.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uzruhpgk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eehjisun.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lhejripr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2esctguei.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdgektq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2billbshf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kubvlonv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnbpskv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vdngtdmh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwamlsns.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcttgnlr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdjrtlm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqyfmzq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rskgvtnz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkisiga.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdawjlck.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmfzrjm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xykztubo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvoscgc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdyexgx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icreadqh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vunaosqu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnfsuig.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uohlwzgn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqsgvkb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgmqrdw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ojowvdlx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcxrncw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjxjaev.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnojkphw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcqxlxa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyxbpbe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2krnbfjqy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2utrawuqo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jldlprny.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xevrebhv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaghnqwz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvglxhce.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaspofc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdseftz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2esqnbuqz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqinnen.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2upkhzdjt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrmfpob.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgykaknb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtjpsly.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2glwpcxwj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aijpixlb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eicupufj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cekicdmd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gjicbrmq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iohcytgf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xhonuiic.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wosufhdt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eeobksjx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxiyzdr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2erahcptd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhwgjbx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaqfmer.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfbtjbd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmrummf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tohfjdbn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2abmffdzk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqpoprq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rknrqvla.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbszlha.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbtvfvb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2esbsbetj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfpwqme.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mmptfzca.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnjvzcy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiybmoi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjcdiql.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzqdkri.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjvgkrm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuzjwea.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zcebmtqw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaxcfck.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxjfwzy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqdhcri.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkpogft.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhogazk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ecimpwdm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhkkjcp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaiggdl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iyszmwgs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2esetepvb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsksurt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhqkhjh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvpeskp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2srzgqnnb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2larvxpoq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zitejiqc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzojgohk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrmayuy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vmztgfcp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2svofdwrt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxsooyq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pynfjlop.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2etqnoptf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eishjnfp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyxrhwn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmgbzzv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxqoxte.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtonxpj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgqhsrf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsccjzx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2suourvvp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bztkmwdo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoolfew.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yiihackh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsdhrof.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2racwqwqn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjehyucr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwksbxc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nxspvlzk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfdhald.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoscbzo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjbqzft.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxyibou.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cpezkeqm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeyntwh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qndnrdgx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2njpizulm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbsjews.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fclblanj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdfpfph.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yipwlmbb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxhdphm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjhkvoq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2daowexhf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nokmzegf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeczkbe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlxnmwj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ozibpbxe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izampfbv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2scrdcnxg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcmbjyh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzbzsui.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxzexss.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwrqfib.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvnjovu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fflpcsfq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmxyaeu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuascqj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fevybimy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjlbawn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzydacj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhrdgoo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrjekgb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhumwzo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2izskgtrs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twuddrxc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2woeamysk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2boknekfy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtusaak.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaddwiv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpzxmhl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nkblkljy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gasvbqiq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hpimnwxf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjivcqz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sludabaj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bogcaiyf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjvwttz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nunaestc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aszqqmer.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2imicwgcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqvmjmt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwccdwc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2izsavxho.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xttadlhp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnprwxq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrgiidk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyahjji.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfokueb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2awnwghdd.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2daccsugj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuxeosk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2shgkpscd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wjedggoa.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuomenr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2prooeamz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oykvqrwc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdktccn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqcanrx.html


<!-- 参考信息 -->