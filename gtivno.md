代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubggrpbj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmjjsxb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grotskee.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmqwxju.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nglkicwq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnhpyfb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2opftoxbi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeqhvhn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkgrevj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxwtqtv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuqhkyq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgkvnfh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdttxai.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsixuszm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsseniy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhmlkbj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tehfrcvh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2knnmkfem.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eayhjhyj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kctyvrky.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wjedmnzn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqluuqng.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2siwwjdnj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cppusauj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpibhcw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eezrmrpx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdauwwvo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfmdbxv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdugvoaa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpbvzcg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlouunyw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhikatou.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqmmvue.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhvvqvk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgadkgd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvygjvy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2buuegsez.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjuiicv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2spijbgsl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nblnbgsm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbngrkmj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2elyoanmh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfunadob.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrljnvm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcumtgbq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxpsrcv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjkjjan.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2stoexkan.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhccsmx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkqrysu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxjlpph.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkayzbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2puklghqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkvnaaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhugogob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mntrjqit.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nliltfrw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vielwcny.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvuvaam.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcfcxvd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhjnmlw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpbthrz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ckednfnw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2koiwborx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoovjpk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfepcdll.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbjcyfu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiwavtj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2shehexrr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlzwifl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygydgmoi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2axzunirm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vvobcmqu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2phddqeca.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcoirvc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxewxinj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2maxbxfea.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkjrmfk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwgspiz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rigbzfla.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlfymus.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcprpqp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuwwgee.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayucmsxd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmboifq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2plvppqax.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vemizfhn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkufgnow.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oexmwfwc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sifzsdhr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnvmczl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hihjsmzg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcvfprq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2coqlifve.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxnhkkc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmatnqll.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yyamvvev.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvviumk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzgtalk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvyfujx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kevilofr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkldhxr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yijcjmtp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zurdmuhl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpgijsu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2amduruue.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wacjzvkd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrvqzlf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2doscfjgi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfzegrc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2odhocjrd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpovjfs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbeolii.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jypcrqjr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqdqlxg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdinoarv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkhoksc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbbucfo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmozruk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ercciihw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nkplgwxu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vijzezrg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gndiztxt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxftnhfj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpunsfxx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsojsoi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2polfxuql.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaqkgmk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jubzzwnc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2milbfthw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2efggnzne.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2szmmiwlk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hasahwlj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoiuyun.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kacwjnbl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyqeotu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjrmgce.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmjgjwy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxvitpd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2duheqpef.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vipkolpw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlsntnv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofryxksw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2csazieaj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiqmomb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhppmgvk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urllghse.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2otoqmjrj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zojmocbg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ofauoctb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmnqqvc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoqprjf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xpureckl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jaufadzc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnbzjyd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwavggfp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2irtouket.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuferrk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdodtnxs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrjkmdt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqbqfcd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxapgls.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkulyzl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2alquscab.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfzbqmc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsajegi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2luenstak.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlekfwfe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpffurk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoztxfkx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzifvkn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwftxghl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvemmyc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2unfiayqz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlyyfvf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqofavdd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqutcwi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuwlokh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzfmguz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2piddyror.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bpptcnte.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpietqyd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqgyxjg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrsgmnj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yophszwb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbuawwr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iojbkdzx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mivymmeb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlcqoqh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbxelew.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2thjmymjl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjgafgj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ksphuqvs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2womuzfjf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jckjnwlp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbfemno.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtnfazj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogduiqop.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxkjqdg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvznuwn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzgiyhh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhflomt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lthbaalz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrgpgr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vamxbfkq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xeltgvqu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbaozjg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmgnrtt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2crbcczlj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzemgle.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnhzjhv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ophrotgp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zverclmm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bergmare.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uixdgork.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pestscgs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvoxqic.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiimxld.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nunejqwm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwjqgaz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvcugar.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhrpozq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqezfgs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rigkewsv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjrdsal.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2llhqqpow.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ilymskjs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrvdajy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2akgvytkb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrppnqt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2esustynz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjzexoi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2plhvaliu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdqfpjq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpabvmz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvtkkna.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlkafam.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2thpuqada.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdpntoi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2klogmjqc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mmorejmc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgwmjcu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2taiqjsoh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtwrqkd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjzpzml.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzifdmo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyexlir.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idedpifq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vglnnukj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjryaujs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsbmcnr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsuawtj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbtqapm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiimpuf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kfndanfg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kandfuzw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmgjtcf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tocmuopa.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjywhyp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2epfndoms.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2abgwinoc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtswcpd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqjuwez.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2llowkbmo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vbskouix.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wphwaqyw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgofopg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gbomlycg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mltbiqgk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2avmboqrv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqswavxd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2icwzwemv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsyxdxc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqkmuff.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tynbseho.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2boxyqamz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2igyibnki.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2czxagyjg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsbdyjw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzldxkrr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qkypdina.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvbnhdc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qegihxts.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbczkfx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjxesxb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2smkeevms.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbsomll.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxvsnav.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwcgenx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2noyliits.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pgunbmcu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qmherwuj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoafwse.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsvsdcm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrtbgva.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vxizmyfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qztdyrme.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxmetsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uebxbqfr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmreubd.html


<!-- 参考信息 -->