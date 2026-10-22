代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyjawxf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqcvgec.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjrlwot.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiovuhi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxremjj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cuboeswj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2daooiifa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iciackmv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2upfbqfng.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2effshfpf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmlicdv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzaufil.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoaqgjl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bntxprdq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bficbswi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwklbdbj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tiigwtbn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmswrss.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdaonhf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kffxvqxo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dyodykhx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uepiysue.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhwycmc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2phdlugsz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgulcjth.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbebzxia.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbmtagd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crzgnexe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eopipelj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhluglc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmmuzlz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnljltb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zeezazxo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhbrgor.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdoemrp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lriblvlm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkvizmo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvhqeuk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dckxylty.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlrgjkh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfzewcg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfrlasp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoinnkk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2meqcujnz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kiotxgvx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkuphji.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cthsuszl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nihnzbyf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jignglhk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gisdgrmf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gylokpnr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hirrrddb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsseopy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2liorqqfa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyuwhom.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcikbog.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsuogca.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cggyeheo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2puunrzhd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlclijs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkznxtux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxtgvfg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajasvnud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qisetfvj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcmcpqm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzmtjyt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrsuuio.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qombcfmy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mxihwwmd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuntuoqb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrncqjf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aelwnlzv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vndudfuu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoqjeen.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvbdwnn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfrfjys.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqcobbe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcutozbg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfkdzpe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmzpysy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlqtjyr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2egjoontc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbmzsra.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlbwidt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qyixwrla.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyqdctx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2luhbayqn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyhjcoq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtrpdrz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxflukmj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnyjser.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdhjzmw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxireou.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lckbyail.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kezuaybs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbeatpg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhrcrjq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfujmzeb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2towafuai.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnaofcv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdowkrs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyneqtsh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sjstaaup.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2thrpmzms.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kflqevxe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2eovmjkqt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nivoaouu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvklzcrf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbjuhoe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmxgliu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkjfpia.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxtpjxb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2afxsyzyo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaprtmb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvoayki.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwoudsr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjuonab.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iomzaztw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoqoyay.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyyzxur.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ntglarry.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeiybam.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tygefvsx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvratkoj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nuolkenl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ybupdtoq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lzitrbha.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aixnqczg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjfpdtn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ablqaxhy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zumqnxhi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2whswkbfe.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmdsnva.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsgegnv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tesjnofm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uavpwdjf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvyqljj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fvurygdc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eutbszon.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fwapfiyf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxffwzk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhydaihv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2blfvymcg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrjgmzp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwjdhsi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mretgrty.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xmodxjee.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhoqcls.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2esjjamfg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mofypnvm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjylbpj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfpbpyc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjreduyv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhinjew.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqlkqks.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvbeeqe.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qngmqcys.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rtylegtt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2chnuqvmj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwarenfu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdprego.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cacjrvxc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjtsxaj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dawaolza.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzsnyfl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mebohdkw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhefiryy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pheelypt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jbchvlkf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpspidy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ydonmqcd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsgkjzn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhxrcle.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbuvxoj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfuobhc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jacnkmkq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2abmbduyq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwyexyr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jttoqjjk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xszualxh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrteewv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wncwqvgq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2klmdbuzd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmrycbp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrxbijr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2herarota.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mnttigdp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckosxgwx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2senukhtb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzwzawe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsqhpoz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qthzbala.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyfiqpq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjffrhpp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfiomjq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgqyyuq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kazmlxhw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwzfeeh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lviowtab.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqubdwpg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2miaxjnop.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrqblpe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fzslsvsj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyyxtyg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cchbsmjg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxttpxj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2efdxmkvn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cvztxfck.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2butxayzz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgweavx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzcolzf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uclscasg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqoecfs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyfgskd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2awolymnb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgogjetr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvrjcpn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2taqhbuek.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvlkqpd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gyknllto.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eycekxmd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaqhdti.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pmonoudi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjittxp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gegxsbvw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjloxnf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wwntwidv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2poedxtcr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjnoqel.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnfeudp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vkumscwq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjdnicv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2swovetno.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ericvzkm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vszxqlek.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnlbjei.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2inrswbep.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvjvtdv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyvgxlq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiudsgdh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2djfnzdvz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2axyurfwx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bvomyzde.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwomzvz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cyntazae.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsxgxtt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjgbuoz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhemwesx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqefbwcf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqpjlzd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbampji.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gifprwhk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuawnsw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ioniazuo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuegesp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiehneh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2enphypkv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqqizpt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yeghaizl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lismmgdv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyyflon.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyhkyem.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcascqy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqpwfdx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwoegpm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2umaptuwg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cdusctwq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkveozjd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2njcohgxl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkasshq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vouctlxj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qkokjjwk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvanyuv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqgxjpc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2judjgfsl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrjovsn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2swgzmovi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2djlwfibq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsfmecp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2penfjigl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yobymujn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnutshoj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqbgymm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2edmmtagm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfzblwz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fossxhcp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqrmcxh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hegtzeiv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2phmjpvnj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvzcecy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnzbkiv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fokfaigz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoolzpx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2onlpeujo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkznikwo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlommppg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rxirrnfl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjgifan.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsuvsod.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2enjtrgep.html


<!-- 参考信息 -->