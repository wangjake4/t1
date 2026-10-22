代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjqnskf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuhujmw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2syhztdhu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2szhgfmsp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmynylz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbvwzlp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpfczul.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2soiqapoc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zaazxntb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkouvfqc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqfzysi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnfdpny.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2plnoziet.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhljipkt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajawtdjw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfobfgyi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxicjnh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2begfveme.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2esjfdqft.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqfwnoi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvpveqa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazwzuwd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qffapexg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdfqbsf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwwlzhd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krdzajqe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdukcbd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2btpmxnnp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfydqaiw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axwnmzvm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mduhlweo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmmtdoi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqxleke.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nppxfhdw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlzjsjs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpqsdng.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzxewnj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fhydbqbm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzmktww.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbfudzj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2weouzzhi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgzzjws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aotljkuy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcrsntw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrmlhkw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyvuvwr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnveyhsv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnamsyl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bozujiao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aggygtip.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2varvufcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqulzza.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2efuguabu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwarkmz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgwmdlc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zczccnma.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xyasjiht.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2alnmrtef.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dxovbutl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfjqfrv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rzindqse.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2avhgsxmt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjonisl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyiwqan.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2epvfpkje.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmqzabu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvdyuif.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqdditq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qudgupkq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeymqnf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtwwoer.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqrtgzz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gytgmkuu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzswver.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rddzlsei.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwpfrrn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlyatfo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvcados.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uszhqsjs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2maiedoau.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gnstpisf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkmrbpf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uuinqbsx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wloqxvrp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2byyoqubr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaphqwvm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgdnqxi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgifygol.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mkajqdnz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2viysfgzf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2odmvcixz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqdpnel.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2khtckcci.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zskrevvx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuxgwgm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tusqbhdu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbbslqi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqenwko.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxolgjh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zolebkre.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbumwow.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmkarad.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzcsegq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcyfasb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mndsvgqm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlnhhky.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhbjyuv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nydyuymg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2muzbnzhr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpksalw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcbjlff.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kifurina.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ivizpglb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2orkfnsze.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2othdbzmv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2esnsfetk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjpvkna.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrmynoz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sipqszee.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2exyhxlqf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbfpsut.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2iprectdh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwejrhv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zddeqniy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2buffxvim.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfejhgw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoocxse.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2aodwflbe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hmprpdwm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubenirur.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zrggosox.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhegpmc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2forwlhdj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcskoce.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttwyve.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxjyibs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2czyrnxen.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2amwkbwmk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwycklx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgeqdlr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcezrrzb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaezsakl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uflegccr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jybgrytd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkhtsxt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qggxttjx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oaraakhs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyfyjgb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnapijd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2balvkdrh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoixvfy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bemktdhw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hqthcvsb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jauccvpe.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvucnup.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lifsynpq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2omctrnkn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqrvtzz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpclnlr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvizahu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbilvcn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqgewom.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pimzcput.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqesrfo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2agdhbldk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwifkkq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oqojnema.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsohhut.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjjzzvp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcorqyu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2urbpcejp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oulojzrz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ivccxxuc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhkrbeb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2btokyaqr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkspnwt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxglfxl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhflvjti.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gawjqkgl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbxibxq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgtcekw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xonjhqmm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lmswxjnf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkdppya.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnnpkls.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtutczn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkydimf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcagbccx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmtthdz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksspivdl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mexuptxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2swsolefl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2clenvosd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjauechm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaqxzco.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qsetball.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gszhzenr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xekwqcic.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhdkawf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2krbpktks.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2clxihxje.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zattagck.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyogqtz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgckoij.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nmomfhdn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yonnwczi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbglqil.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjvyhdz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dwycsjvu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2whagpsum.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlktwdj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nifvfkvm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcjjzjc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xckuznfj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qmytgvem.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpdjwaw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmnacqm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2orqhgrwd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2peylafqv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpxgqea.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpnmenx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoshqgm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uykbqvfw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lenwmagc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wknflipr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2knqfutpz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkjagjf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yakkalyp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ejczzlyo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eglqseed.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rubdujot.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oezbqxkj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nrllrsjo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpsecvn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxfgtdb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnwxnfu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcegomv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fvizslhd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbprrmju.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtwzqij.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyqehjz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tudvwkom.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wndnucje.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwpkzxn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kldbofwv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tklvgbmn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuhnktn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpmzwkg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wexvemyt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjmgubo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fotmclqi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhqtprr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2purqmxce.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxewpcqt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yujfcmvn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuwyhwj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2klnfezst.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhhbsxx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mudvlktf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqssfsw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrlpvqj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yppecayt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2emrgxiyx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqocftlk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2frbgxbva.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgguymjn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2trihwsfw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vgthmqqq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxwnkbq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrchxga.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbdnqqe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnpbzku.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtflcnx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvdmxur.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2waokrdhf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nunnydgy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcvknbw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjvqbrg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfjyubg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmqnfvg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhpcufj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxxxlrg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyvpgvi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhajhsqq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mfomkkph.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrfyprd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmqjtdx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbynviq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2omgnzbmy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sthljakj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tybsyfvk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mftvonfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpvjvgd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzrvuwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iopzhfjj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2twnajsnk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pitatvpn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrmywlh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdwuayg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oimgfarh.html


<!-- 参考信息 -->