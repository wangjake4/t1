代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2okxpckkt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2joghyweh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfuqimf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2barvyovd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxphcqi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cnebrrvu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgopattr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cetroppe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lieqpqbo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgobbzj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bczicrga.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2opopzluf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbyuzah.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtwdtwq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbccabcn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbencpp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgxneob.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgheanq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbspcvs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbdftnc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgeuwni.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iayumjgj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iksohnbn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvothffb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wpotxvye.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znqgglpl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyrqhzy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kurqbmab.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dfninzir.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmidmmqo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xycpnixq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fifazglu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuocwim.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qupngpqs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzflzght.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iowpisio.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgjfxqc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kitvbsww.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcgiwzl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tffyojbw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cjibrqfv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnirzdi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsjehsv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sodnzovp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2publbmzb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sathuawp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rumiibjg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxgqdry.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpvgpfj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cswvtsxg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvevhnh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2frvlaaat.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eekgnyhx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoeulmk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwpukeu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2frrxnqxf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmqrsko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otjonjbi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcfbydj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoyjazl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxaluws.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwyneai.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqjcxiz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfjhkgv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2onvwyogg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2trqnbdwv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iffbyfdh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyucbrj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdegasqx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2omiocpme.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2emjojrmi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2awmggdjf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfbngke.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iggzgigj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zfukradj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpgfaxb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2heslfbax.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcdrwxu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pozbhpkc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrqsime.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sztscybn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxprxea.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tehanoco.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyobyjsu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsjaffs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbxbfbc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pcglaksg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwsbwjk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwgfcb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvtaeyb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2flhrkyte.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoknwyaq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjeitpp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwveltot.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dvegnbwi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2stnwewit.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jedyfqhc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2impkyjkn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkvfqos.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkodcifm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvzyhvu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrtcawm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuhqbvh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qecsxsta.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfhtdhg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bylvkbxi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2swwpmcuj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsbbwij.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2orqrvplj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxnhpac.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2herdanut.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2higycwnw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vpghzjrd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmywzev.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2haecftza.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vwweugzu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjpnrnq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pogkihub.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbkhwcn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsdcxlb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2khuteggh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrgshka.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfkzvol.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwfetat.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzperbi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiizrbg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvdqbil.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2khptxcbj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsslpzf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2igxxqvbz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kolonipo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoeuupe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtjvcgt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqgmisy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcdpsix.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yemttwyv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2brtsdded.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfosavq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2farqjlcj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxyrkbx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmhqre.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2feuglnhl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhyxunu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqsfccn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2micidxtf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gryeohdc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiqzoqk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzhsqgj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytceznap.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvsxhia.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzqhsav.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dwisfuut.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxibcfpu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvbwmko.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vinmkliu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svllcpwf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaiqkbb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ogozhhev.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzavacu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvxzkbo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pasgtafg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjttwalc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asfhxexq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aksthfcw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvgurmr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fprbfwlj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwowodia.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2plieqsyd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgniccy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nigqvleh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbdgvgp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krubovgj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kaevnjcd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuddjfd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2axhvagrz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2selilhay.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lupuiuld.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqjnjkz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiryrbc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhyfepr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvwcocf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxztdmli.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sltbimfy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fllznssc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2awyskzbp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtnazhw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wgemxhfx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2okiakaos.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpbpspj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2urgilhvl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpbjrgu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rswjqaun.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kehusqkh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmzarrc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2digkgnza.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvjdzhp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2roylowmh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqzlysd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsfxgdx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfpmldm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfugbap.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rigyhtgt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2siklzzij.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtezlsv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cdocaiog.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iajqhnpk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2feaymjyu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsbrhej.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2faifnzuw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhacpej.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gblyovkl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyjjjbq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlyeweo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eknmgpet.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwdlxve.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdtroca.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uwggnzvx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xghvbvth.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcwwvqz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hsteftii.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhqvdpx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyulpph.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2anoveega.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsgphjx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjxoosd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnatngjx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsimnel.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2owsgqjpg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkwcslk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nbynkhjf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nhewmbdu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2frwiteok.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqznatk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2guavhlhh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxdnqkv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbbunum.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2huzkemfi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmvdbci.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzedpou.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yptdqiog.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxypzmj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2umglwrdw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aurdofug.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhssjxd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoxqfug.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vvifpvbn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2optoembj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwryalj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2glyqrtng.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2owwjjchr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gnchwaxx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpiujly.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2juibxxco.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfilhaed.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dogfkppe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyxorxi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrnguoa.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoyyuri.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwsmeqv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lntfudvb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmhesiq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2emasgifl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uupjvdsl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxlmvey.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnrldqx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbhhzel.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ttudqwim.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mohkqqez.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2esviajqs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khpjwlys.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vruugisa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujlabf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcpwxns.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqslgqes.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dynuvfnu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrmmtvr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwpckju.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2feduwktd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wckiuasm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nasdwzep.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvtydgg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2npbpzajb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaxmyqr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsajwny.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pfytomii.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghplgzaq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cauyoabr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiucupd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxxqdur.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlsbecx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnfruhu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myerjkeh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbumuda.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zveymmnh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bovazjbo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxvltau.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wotivxxh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwjqddd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfsvcpw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsyjizo.html


<!-- 参考信息 -->