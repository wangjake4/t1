代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfllaac.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwysznxx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwwrqwx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrhjcmo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2imxpaflp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2psfkpcpv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwezwgj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuvauzu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vumbkmgu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbfvgkg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqaetsd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rneeufbj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbdzwff.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtszymi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdbekjf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbbgdms.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtdpqno.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2earvuthu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zttgccdx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwzdlqh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwranaw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbhuyqc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2axouvkpl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrfnuvy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fofcbnag.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jylmzmcf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbnuiky.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nenyncea.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lagofjkt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2decmmosd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spmgkvwv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyycvket.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtydeci.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyeitzj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvohoog.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkmsopp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxibwm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mswftnji.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdfswgm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxayseg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmnzqqy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eykcbhtk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isnkhlzy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvjqopv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtjxadz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrggaqs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzttvxgi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pxovfilb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eroobrlj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvglqqg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eltayclg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpgqakv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2igfqyfni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlokcrge.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqlkoku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjpvgmb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2omxpwopv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkztyot.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmdktgt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gofihcjp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2leqznyip.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pipedjxn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkismdg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2izbxvjvc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2akbdkunc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpnodpt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2omhzytav.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdyxzif.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sirdwmkm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtehcyn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnodjpn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsisbgo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeuyemy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2iocsduta.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jiofjfvb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyqoniv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2abchleae.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plqgjvyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sapztyfz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyfkdnd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffznbofz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpqsedm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2stlfmmyz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhogayc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2shbarcgu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuwelmq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yilufejq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2duvemlrx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nejjpmvy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbjvwrn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvpfcii.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqvdudr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jikazeua.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zurqghyl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhnkfwg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdkfqdv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdetmvm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qczqtdon.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uarcpftj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ryadmmwr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaekfnf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oahppawm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whhzymqt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkqbnft.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2brfhnwnl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2avdtetzc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2opgwaukq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjalxwhv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vnipajlm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2arisvwqr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2convoqea.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjeeuoo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtzulyc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uaisugno.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmzegbr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2taktxsqo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ngelefiz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qrncdzfv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2svfwcvvg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2flcxwevx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xrararus.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwzsasc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rphpfogy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2emfotkid.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkvyhun.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2voxbliwo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ustafmlj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnujglzu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2icqjpvgq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eitfpczp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2miewpyhk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uinulham.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2blxxkxwy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwodrlow.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbaxwwz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgiocmj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mynzrkck.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrmnpmz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2htuhhpgi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhqgrwf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtnqglw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2emwquqll.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdqkkks.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwehnuz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lapnlsis.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgrukra.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2poucviin.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrtbeef.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amxbxezf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2agtowpbp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnotfoa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjuceju.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nqllppkx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2drpxmxwi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdzqdow.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjblcfo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2knlxdjix.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kviqvehb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awprbrfd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoayphv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxhrfop.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jswouaiu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcshbhtu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkyhlty.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzbgczi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmijbns.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jefyviwi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqmqwck.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvysqpo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbldabsr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlzuqvs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrxiyin.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ckytoyuv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxventkf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwkspkj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jioleljl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfbhuzm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqojhhi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2juvaaruc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpqnskr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xtguthaj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwbeeut.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dsygmhcr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkcqths.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqaormo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anejjiau.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wodamamy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hofdbepa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bexcdvsq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohreqceo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uccptskr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouirwwek.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2onudiyut.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfxptug.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcyhcuh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ansdjkoq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2okhqghcm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnhpbjk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkquyqa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkwuqfa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvejkik.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkndccjf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcapuyf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2efntxeyv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxsblxl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uokbcbos.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrghbxb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlndbzsy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fegoqfjv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2itucqgsy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzjqsow.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjorwpa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmvdtub.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2icokhxpm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hukbfign.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pttigkkl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nzexijpt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaovwwu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2udwrqjtc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2omtvdrej.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjgrmit.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2twsxxqll.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhbekre.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlkcdmd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lxurmwiw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhematy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2clzymlpf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjclniv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wngngxav.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgijhncq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmayghd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aupsziie.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2krfqowgf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpxegoj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqemmbe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmobvoei.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arkbrnwn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqqdvys.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmcqcdc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzowsbs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqalthr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2orfgattg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyggkzcq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hciiuubj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zehfarfz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnfgbnz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzgyjjx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sogtqunz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2htgavqgm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjoblbq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnbgeiw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvzbdha.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aoktntkh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lholxizo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwytfue.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2meatbbgg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hzflelvr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2awvmtmve.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlmdfgt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2waqwzqtg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rafsyyls.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbioidaq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2soaympfw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezioiwzm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbjecuy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2asyugnqu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cckjfwvo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpgwzuh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgjxbcb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwijibc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgszqwr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zianjxbv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuxbeze.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpenbxcy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgooitq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnlbtel.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpyptqu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzztowte.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqnyewc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwsjkxk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nwffhkxt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcspkhiq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwywvuvy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbmlyrz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mniozdup.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkcwntv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2paslwvyn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnlgsng.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtiigel.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kzirruiy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2iwunzqdi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lomsqody.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2srvnqlry.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2oovwqkwl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkiscbw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwipnvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2telojjap.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuhhwwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcziathr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rzryelhr.html


<!-- 参考信息 -->