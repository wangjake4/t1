代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgexlsh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gvixluao.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyjdivv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrxquws.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qaotbnux.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kubfkkhz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exjpeyly.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxcwyfr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdijlzn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxxwcai.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnleaca.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjshjtao.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2loidzxae.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2begnarsg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjqcfkm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ujegrkdp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoebtey.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tleltfwx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hrietosf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wasrxqih.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdiibcy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbuimth.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxmojar.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnpltzo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkudawo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjcajnt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoosbxk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taehrihu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2svddybii.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clwjzcbz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrrfcdr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtnjlmf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxvveug.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evdpvwxy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqoayju.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkllqot.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmxqdfg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rozdcbgm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptboecnf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sruotveo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhpevog.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrcllyl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxijwfrn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zssugjix.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzemzut.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2avmaqclz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obcknqhh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvbmmls.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbmkciq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmqepjq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfmnacz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wfptljfs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eslpuooj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrjxprn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfynauvb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2swkvrloo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rscnoyjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmgceax.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnusoprs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvejird.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyqceep.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cpidyuho.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxfqrwl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2woantlqw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2huvyfufv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2toyhcyqd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2berqkskt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zetbefyd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zneaoeun.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nghtvtcn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2klosqemy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqpbslc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqlxxcd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwofbqpg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2brvfdsyi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2agofxjfy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2noixffea.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyentksq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ybylwwje.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2daqlluds.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gppeepsy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyhfrgz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hzksjfvd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwezijpi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyxgzyf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2npsimyol.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aaglpvwm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexovhba.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2aooeuwql.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jihvptcv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzwakip.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmhhnjr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qprtxhib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgzugwe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcqdabp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrjieed.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqggxgq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfvmeoh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxwvjdk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zelvauod.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2slbfvnxn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2neohphgq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2htvkohkw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2osuifepa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmyemrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjsrkke.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2czcxmycg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkhfnab.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2utppgzwd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2psiguhic.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2viizuvnz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwqixaj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbsgntc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tabcwzlr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dsctpztj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnrrzij.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vgruhphu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqarczd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ynblvjxc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2egcdwibf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkicchj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pslokfrw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jffyerdv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qurcwzza.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2awmthjnk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2myrnbjsj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvptzar.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2guxsmbjk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpzwgge.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2adfrczjt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2leuvvuqs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgpnufr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tzekuzgh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsqgcpu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsogkgl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuvqwcp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gvamgakg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqivoibh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gwstxyop.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqzolco.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2knxbnwrg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tawcnnla.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zabxikfy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyzwsgx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2preestxg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkniullh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoryupfc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjibhhln.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twdksrmz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgzrrvw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmmlsdk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlhczfr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qoidmzun.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdgcprh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxamout.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxkbmtr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwqtidi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2emirotwt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2szblbygp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzwagrt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sighrsab.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2equupitj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwosdhrx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmmzohg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgjhpms.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zstapmrw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pknyoksz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsadquz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2drfczcxf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlalltw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhvypiy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiqrkdl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsgbvet.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afskenei.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lokvfpeg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhefscsl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eklhknom.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zytksgcn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnyadyd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpmrccm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xujugsqs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2giftadlo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2koubtory.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tujmypsi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gipgmork.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2spihffjj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2trwqevpf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2twedgwlc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpyskkz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2luzmgqka.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ofldtwzb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwkohqm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eqldxxqc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzosrbm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2amyfewwm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pddyobpq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lljgilbb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwdhrfh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uocvfvmn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjonubco.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqdeucn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqboysp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2czfvkusw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzntadp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2aibfjjqx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsprwdvl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xchvehsd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzdepbm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2icssgrxe.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmbinoo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aupeowsr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmgbstw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2miswanlq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2exgvtrgn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fbieiqsv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tustuvsb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cykygdwr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rizyqgmo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oitvoyqc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvdqpnb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgjcoli.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsgszou.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wacbwenu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbqimuj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fyilxbtt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2falqtqkm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2srrebbrg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrhnzls.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyiytnd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ekirnfro.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2alnnegih.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbdqelg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2igprddbj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2herdkocw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfwdhxt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2icalrlih.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bnguicfl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpljycvs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krezbjdf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpboqgu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lboerqck.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtzfpvf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtqosqg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2femosrds.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2awadoenc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqhfiwz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpevjfun.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vamqmhop.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjfsppa.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ciumthkm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qndodape.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrrgjbq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2opnlaxuk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgklzbb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kywbzpgw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uccbozpt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wpztzbby.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjccdix.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzxdnsp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqquutkn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcagkmb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxuccmd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yrebznbn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyporrrt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ympmfvav.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dinpallq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sfilvsir.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2njetlvhl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xzreivol.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zltkbvmx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dqghtlij.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnixobaz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rlizvmqc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrbfwif.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgythct.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcsefbo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgcidhw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2phlnuusd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lllkpfti.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2munacfwp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtibdwl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfqaitd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aunrimln.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxjbdov.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuitfag.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnfirqu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsxknsn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmyehpk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2irshykvi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwexnyzj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxwolmt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fntwstap.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fvddqwmw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoxemcl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuipmxw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2llvvzstp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnvnjzc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xensrznc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2oipzrrxe.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiizgas.html


<!-- 参考信息 -->