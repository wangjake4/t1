代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2luhliult.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2merieemo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxuldpb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhacbai.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gchafrep.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuhvicq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lxopmlen.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvsjzle.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bagofkcf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iquntiep.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzjjokg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqihwlq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfzotfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prrpvout.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwscpnst.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqyhemw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oocoeumo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhjjqtz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2plfejgaw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2onvpozhp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ysllwkss.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uscgkjhl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oihnslnk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zetfdkcv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpqzaby.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsxvezj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbaawdi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkhjjqq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvegsdjm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2knwgheci.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qylksgou.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvpirft.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnxnamz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jiervpen.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2reohqqji.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmhfpso.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsrtpvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hscgcehf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsecinpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ricskdqf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2esovfdyw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhuriyo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyciaff.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rablaiwc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyfxkbv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzayauj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxjcigx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnjiocb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuundaw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsbajkj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnlnvvi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuixjmxd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtipopv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyakpoa.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvbgbzi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtsbkys.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrkmclx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbulqee.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgcogyh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ustfdjdv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vewmuwef.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtitnebu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2spbtnzyu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpgjjec.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uebcaeqb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejynreeg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbhcbgl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtvnwel.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfylvfr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2trhitaae.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uznnuqks.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjjcyqj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eydqtmuv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzrdxxm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmcmaza.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hupkntrk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzobxku.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlczgya.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfpsjoa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbebxxvr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rmluejzb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxbadsp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtvnuld.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgvjuuj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaltgsa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtgjogn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2szvteocz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfajpfj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuysojm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywvqvp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2prafzcud.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmoaiue.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2osclstau.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcardvb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsuowlu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdbfutd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzpnvid.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2slrwemjk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrvnwoo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fktexmqu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbkdade.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jecrjayg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnpzmry.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiqvlkc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ijflavfl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2urzteyyu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qksrkqcg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuystccu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2swvosvsj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaiqcfy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmeovdx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaohtav.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aleomfxi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oumtybtm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oztqzzji.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fyquhrji.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuasukl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhvbaiq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oddvlxsz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elqebnov.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpfagzn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2waooulhz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdloybl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2idagptdf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2akwpzgfa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2siaxgion.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icyvvuwj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgeufer.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yllgaebq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nclzctmw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzrpefp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvjhpna.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkklowx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ibodvhin.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxtvxbq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxnbrgk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmyuixu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuidifb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fffjmtre.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxlwahh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2twgmgagp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiokwzo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrxqfeb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2alpcrzqj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iomdpzys.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpxujao.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuxkycl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2doiznzyh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxbolnv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwdkrlf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaketdr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijxqtcb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqnkmyt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfyrmif.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eghbigee.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2azazyfyg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2goimorkd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgyqxra.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnouzjfw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhhviwp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uapngjhe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxynfbqf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kooeylny.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtkqxqz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnwodbg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyphgwo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2omshtwqi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2elzpeglt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gdczvwbf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdyqvpn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfhuejf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkyelgh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2znxjwxnl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcfvxjj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yiefkqym.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yugsftxf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2apyzrzrd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omwvegbj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2exipqkgs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvfrukx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiulhga.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeokpwz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwwewdf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jwevsxkv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlujeay.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzcmrrg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npuzfkci.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2aehjswzx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rupqyqnk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ginpzkye.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ryngzqyy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzfyqaq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2peltyald.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rqehlvok.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2meyvmwaj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxxwcxh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2aalcgkrb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkkvvqx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhaxxkr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ezejzdjr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vsblkzoi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xfldltua.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiqoxow.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnetlycn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpxwhrf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iilrupfj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcxgcqn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2aywhhzky.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsmlhqj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gehaxqom.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mujdjfvb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkycmbi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrbvkmu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgbskzs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfyjrdh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuyevmp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vwozwlws.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvknwzf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2crmurpoa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwnwdoa.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hqidtxiy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cipncxbq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ipewspgs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcatdbus.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvazvif.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2yyddclnn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2altmgulj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfllfbkn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2etvgicfv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2akwdlypy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ievqzsda.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcxaazl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfhplcu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xakzkihn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2reuxgjrt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nflplfnx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wawkgzsi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcncxnd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gkywzwto.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwtxtnw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yetficwz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuenynvr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjlprxi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgcmmne.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ojedtarq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwbgeui.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rkceufuq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yufztoec.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfbhqcs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdclbebp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfrbroq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rtquwzwf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sasmxfsb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyyxlib.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wigtmwcn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jscpiyci.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2slhiirdo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsrofwh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnyioxb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcbjmgq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dxamxuan.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmcdtzu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdzxlyd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nflujeui.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2enbcodji.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wepyunxg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwjpkrh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tatgyoxg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2znbwzuev.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdylgqe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2egqfkrwa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abkytjoh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tyheozjz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrwwkzz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tvedxxtu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2oooomuye.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiovquk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbfqxaj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxwufhq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvhegzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbezncz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmaslfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnwithj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zaerynle.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkyzqok.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2anbhajmg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhdjmbn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzfunue.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bswqvwwx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfproie.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrocopv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdkslgh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fedtxtwo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzxdpex.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqgkgbr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmfcpig.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2esyntymh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vryrfych.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcyvwac.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqfvtwo.html


<!-- 参考信息 -->