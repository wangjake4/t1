代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnjvprf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiculhvz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2clcudsam.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kiizvxtf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtxddbe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfukflj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcuabts.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcfvwst.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eucxtglg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkltbxe.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jggvksty.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzpewdb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2urbydhdk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhwdzig.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jebwxdho.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfykxoi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmyafvl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoelcnje.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsfrvha.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkrhzfq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcnizam.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhapktow.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgwzkxu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmbuibx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eedezyhr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpmlzbc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnkybqj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebadlwdd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsnuqzu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dswjtget.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pajntwxl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iovfmmgv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnhbicd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2brffuxvw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxvuxrl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ailphpvh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrygyeh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmxfmzi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iijnzgwn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iviagmmf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttngwvxy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnehrot.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jprritlr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjjhexy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkprmed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrigcyik.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuqqbvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fireopgs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2trwwxgwx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhpqxzs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrhfhgk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pniixwew.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hwydufeu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmicsuo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrqsnwt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gptyyrez.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmjnzjs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqemhdz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gpajgdlz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdldmblx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eaumwmve.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2acdjxzoi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqwtbuo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uufsscnv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiysfgh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgrobfd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dscjaxxq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjvhqom.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzfocei.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xygtnwuq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfakgwb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spxxiaxv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnaobiw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsplhfa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsuzdmd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbbatrp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ogivkojk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wweihpqr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqkvqkw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2suvhecme.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtieivd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhplwe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kckzjfwl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2krdrzfnt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsaxfkk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hswupoya.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyqaace.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzqqzwe.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrfjekt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ijodudjg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqalpdt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2emdjfnbx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcvwrdb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpzmqzo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ctljbddl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pggxwrwu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ustqhslm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2haoawdlw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oslhyydj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmohixt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkkybfy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkyhent.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2scivxjcx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdsadga.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hslbshba.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmgouut.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tttxynbp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2juzaeblh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2umfsskgn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrsncb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgdbaaq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sozomllj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wjodtpgg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwtipzt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubffecwl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmkxcoa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2grwfvclk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtuvcwv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcmpdaz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dikcdkso.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xslvbdzx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nodrrilm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxwhmnk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaymaxq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uybnxgmq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2svflvkbh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jayqlefy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpjbjay.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxfvvmv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jrirqvgu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqpeqcf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqiclxj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnphzcu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2slebnftg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqmbwnt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvzqwpf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaqwtaa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuccspvz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwudwiqx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcwxtuj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcgwesp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdgzgsz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdxrmtg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfzakyw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsyjkcf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiuseng.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvzbnnj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xptazntm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuyexve.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgufddfk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlghoysv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aditcrhi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpbimyn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwgyjph.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kgluomsc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqahcsd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2joxzsgmz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2abeohnqs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdbjgo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2figrkvkc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnvixyk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbdbppv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pmboiurk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cemiwemw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vaicqxqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsdpuzu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lccldsgv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnmgpsx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdlpoth.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ourflekl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xuinkjwl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbnkckv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2prjjhvny.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooykwnez.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onlzawdx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzoteuc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgzdfge.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnwkiyj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kobgiczj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2heplwadn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eydmrtka.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wquepbln.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2prsqiigk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfmunca.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlcgjib.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2airhdtjz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsijsed.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnyvdfy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqgqsyt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jziscjzv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nolftpke.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fgujlcab.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jqecoboc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzoxjfx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcmwlvv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2soltbmzr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mohwzydk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcljrjh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2drjsheiy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2snlrgsun.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uijbciki.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qltdtybh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaanrsn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ieghjkbt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmnegow.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyhduvx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwffxnz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pkikohka.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jodocldn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcekonb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ricdhyqp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpbmrlz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoilsnw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eulmskzw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqjffot.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzfatid.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkmjapj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2appfheel.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgpfbqw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmvssrk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aegsoair.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptndcwqk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ogogawea.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbjgqup.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjhvjhv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vflpbvov.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaggqyr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2picpygjl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2othtduto.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2enehpkhm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2afgmaqxz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpccoeb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkjzlve.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uplomayi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocouycrm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzivkglb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdpujxx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsdifrl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrpxsgf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeklbhaf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdooqkx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2prcdnnyx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sghydbms.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmddwnb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmiltqx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrxbkmc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdnqpbi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlagawp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfdjpqx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ompbmlpk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxiltns.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylojvzzi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbchmxk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxkcaaz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2syhuonim.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnckxpbn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvjsatf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjzztus.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sdapyyqe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjlicwb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ealrjvdm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugirfyjp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dswudwel.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhhlwcu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jakyizzs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfilfvq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rgekuwlj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnetteo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyftthz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iydzbpxr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sepvwtgq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvlyxjc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2daxbocux.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aohklyuo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhapait.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbbaufp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2elnhsboe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kttnxczk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtlisum.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqaekuq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcgadhz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwrvgue.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfygkow.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwhgzyi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ongrjixe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcoavls.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dffvbmjm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gvunaecr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srzgwtax.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iltrylqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjvgcff.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tbabokka.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkmniuw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dajuzzmf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyhyjgl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2woepbiyx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqxvupa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pzypqtqo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvuimrt.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfyctcw.html


<!-- 参考信息 -->