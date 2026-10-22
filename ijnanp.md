代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2flvkyadr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgztgyf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvypzah.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbkhltz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvzrybt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcniowjb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqonveez.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrruotcf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wpktamov.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwsjpej.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efjdcdnp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwdplgi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wshjfpru.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igihlghe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kudlkqeo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpuvskg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiorvmu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2opiksvml.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eetxetjv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqkcfew.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqyseml.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtrngsm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrtzgfk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wjunyhng.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rumwolnt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eympzevw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2winujpak.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bofdgluw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2teipolkq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuoutgg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgwqrmk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2akmntkbp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pcirrrmj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuvwglu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hufzlpys.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cuabbqba.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoldclf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scszgdak.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trxtbnnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcisuhh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyuieyj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sytgrwbn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sybnhrdt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agqkqdqo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwwsmsa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxjyjho.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tttkwwhg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2adyzhmsu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ioydagho.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzfchqa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfhuyqj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwawcns.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrjhnjw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwpbnpy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2trkyyysp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhlstul.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyruian.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tphajvlt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2osqutbck.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cijeyfnu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xedzfrkv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswlaofj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wgejjhgj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxvbpkw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iunwqbfq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlgcqvs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2glomgfho.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlerhhdm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpicwxs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnndecso.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsylnho.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2axzdekrs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lsasrqyv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kivppeoq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2olciizme.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2srjnqsjy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvtnapg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsnzbwe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jsafftyo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cekjomfv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mmegzjmk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oylpqotg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwnvbxw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtekpzha.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klbtihgy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdlgwqr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlxxfms.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpfodql.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fujuoenz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzpqxkx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xiahzfjr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iykfjvla.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oixiplrl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmrfzuq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqkppsl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2avagzxxh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaqhysj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hrclgdbw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqjmwlh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2soaqhtzx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hpskxrxj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvsixzr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzknsty.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaqjfcp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgrwidz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyriclpc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcwhabr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxjgjwc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2shwxhnjd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxmzysz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fshjqvwy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyqlpno.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2usmhoiby.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgdwixj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lphkbttz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmhasgm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyggxso.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2asrpsxaq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bavuehcy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2quotspjz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpfnbbb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzbsklr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2htmkuiti.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxozabq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjuvdhf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgxsukf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvyhilm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkjplss.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdhjozj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhkvlsc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnhgumf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtjbwuj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqylqkze.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrzqogr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sscmwvuh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iugikuub.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iomgwaji.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nxusqnrx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtiafps.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqswaok.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2acjcscte.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjxodz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxpdcmu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmvyefm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fbytzbfa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2yasmkgkm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlpnvvr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzifagi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2enrdkhjx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tznsuqmq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2egimypnf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpzghec.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zetgxsxy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdvxppp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsdrofo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdirpngy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uytkddgn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfxownk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pogcwcoq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kspjeblw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zqivbvjj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpttxxhk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzqpebd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxivhte.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqatkxw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoahkig.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dznvgfnj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkhzxhe.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzjopxk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xntiggjw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvdfulu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nptjztru.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwpzhmz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoxwsdb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrpwumb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrpogec.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvncmtj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krsyxrix.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkebbhh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdazrzx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sumnbtix.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cenwsvlj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zrncenvw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgrxjgr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkdfbeq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lplcgvek.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpezywdm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftplisri.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhytxgu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkbnbnu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mietzkqf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgjjwsv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbyduam.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgsmwxn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sngcfflg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tswlwpmq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwdfexv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpaacjt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiqgvlf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2witvxtum.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyodlnn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoiyfow.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zehrvbbm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgdlmwe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bzodqvui.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ontebkci.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2akuzjghv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnzggxq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nqushjdv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2isicjvth.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tzocodau.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwqjlsx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2smtqpcla.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmquuxy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cchojrbn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmehnbw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zpudtgnp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfgwufi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idonikgr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2snduktnj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umcjgxin.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhkrbzc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aksdvkcb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yedoolkg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vycpkzql.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2etxghsgc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cysnsvli.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qirszicv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmpddys.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2otsltzng.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tspvnvze.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlgakpl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2twxlqzdw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sivyvwvp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzycfrp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwygoel.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmwqnrg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gxosukvi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfykaivn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgrqtav.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpbtzoo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhdraaj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2apqulitm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2escwtwva.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbfddvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrlvnio.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwvxhns.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvfzxke.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sgshtqdx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgjdhup.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvvjjz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2utdazpvr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgjijyn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojimqcr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdhdgqc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2abvjntyx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ravvqwlx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhoijgy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgsrllt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2evmjnffj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eceuomyv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vafeuopn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrlensg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgelhix.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2icqzxyoy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jroodpxv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qkudgglt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2khyodnpc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmlplsb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfriswk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2afnwdzjl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkkqmgs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvkwkpk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiisufj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kotqxnaz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhxhokr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jmazfytd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pastclmt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxpmfpl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2liviuxsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ounhivgm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkxdoqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbmsaec.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2weklrkxr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lqalwind.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyddith.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvcqoph.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwcqbwk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2liaaicxi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbdemig.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjgcxtn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uruajdcs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzpsoxr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pkibejuz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2haxldypq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vjshxeei.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zxirhspu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlungal.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vwayluty.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2glppyjbd.html


<!-- 参考信息 -->