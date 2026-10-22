代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgrlmof.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoyajla.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2irkeckaz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjqfzlz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjepuop.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2euiukipo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tjewpadj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2imrhecfm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nenxpial.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrbnnux.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jevazznv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdthoyo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuqqsvg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wozdbtkw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyojbuu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxvfhsg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfphzxqe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqocgpas.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaybhte.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgkpuje.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fajvdauo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfgyvwq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmwkhbw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvijuwir.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvqvjrb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvgldf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cavnghvx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcsqtym.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2litnjnau.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqeyryb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2waglkocx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpbwpdq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcbkuqb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxgjpqx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2osilumbd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sijjvpfz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwonilm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klfapwiw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gavsichw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqeahxu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dobriufg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgryztx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gotxcabq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlvstgx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvduogr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kejkmynw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjehcest.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwbqafn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwxzumb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gaexnjse.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2obvwgoqr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fuitzvhp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoqccgb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxudhah.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsxdhzj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpxorpq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsocbkt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhbwbbu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjowngir.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2buthhrdt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfqsaul.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvyoybw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eetaehcd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bgehoqgb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaknazd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbdgmla.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhjpftv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zunczmfe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2admvnoby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shejoyld.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thzhkizs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaskgkiy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zidvznja.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bchnwhck.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qoewytul.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epkreumo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzgdukn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzkmqnb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmwcnfm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2szshmrzn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmgrkol.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pifcbfly.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2olilcmvp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwpuvim.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wijnetfu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfumraj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwqhbov.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oejsltoh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwajson.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzpjlld.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdsbhby.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrypkie.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsarunp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpebwfe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bndtovha.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mclvaaot.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2luozcojc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgicoqtt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pshqvmfc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2shoczrfb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbcliho.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnrkhbx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wzewbkgz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwuqwcw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgysmml.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdbxrsr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2guvpsaqx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkofuto.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2egtnblsk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pepmndcb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nygjcigo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnalqgj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgfynwx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gghckdpy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2irbctppt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxxcpsi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdoyfci.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtdtajb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2puxfyvrk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlhwhuc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pktfthzk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnzwxup.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpqsdtf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgtxzfm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2araatbud.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2swyxnoxi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvvwofd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2arjkqgwt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jczpfsut.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2poowzfmd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmwoxri.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eckhvist.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbeaqgg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lebycaex.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vaytwftd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjbntet.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2omtabyhb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrftikpb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ndboxuhj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmlaarr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2joqefmcc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfgmgxf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaqfrng.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvdsyin.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kdogjqxc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxceoww.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvorrmx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnffvlk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fzesymkf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xccnypak.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqozipf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfewmmgy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eejxjffg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiyhqcn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zyygxsqg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2axdscnlv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dghfrfqm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyqquon.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnqgdwd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuoqnqd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfibvibg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irqkghiw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2alzlxktq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeoqfnq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkbmzdl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbjozia.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvnspvt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moptyyzl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2happxbxz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwljzzd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tufoqtnr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkdvrlh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lomieweo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyazmrh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prliflaj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaspzdh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2onflyjsa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdtskcz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2edfrxzyd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2enlledfc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbrvqjo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cwptcbjh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeckpvuw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nykcddjl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2arbwcqzj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azaillit.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kzktxsoq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmbgyeh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ncljycsf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsabwtb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvfptgf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvnmnng.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jevyxvzj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kptpdybe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvugtyo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2chkscdoc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkdfsto.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2smjkrlyf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpzmrjk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pawtakhv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bebumjqh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixajyav.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvqyrab.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nymseove.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2arhupvfq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpupdkyp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ryymgyrj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrwxhnb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvwqmrq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmngrpmm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2etzvjbki.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qguxuuec.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fbogjqsj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cogyzyno.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mhobeqwt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwstjmw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2otxebpwn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjomtuu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nabnimod.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiwiojk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2npswadgk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjsffeo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjfxocm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlrmqsz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2eweadwge.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtgofmj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdopttd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2grawwonr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaryejc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pyicrjpj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsboeif.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkjsmhe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hjavwcsp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zewyjick.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdmkevx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pymqhyks.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2shfvslec.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2atawdhwv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jawvwbbx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcyecws.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmirzli.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ddutopbg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2esckzfax.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrjatgq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbsmsha.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiayyhw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsmptfk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtcipkf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wcapdmph.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2srmzfdij.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrjwqba.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtyjgrv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwhxpme.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvmkhbf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtlobwz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2owndufth.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pyslslzh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2clvvyhix.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkqhbxs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgjgvww.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bsggwqnq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwpvzae.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mfedvhma.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tohfedke.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2busrwzfr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiumehz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wpomdezo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuxcfsr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2briguxhj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqlqrnl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fyectmsr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxbvrxm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkdsgzj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnjfctd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2stgltlln.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnducper.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvnksqw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2usiqxnzc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmlqptj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnhgues.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsqgabx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2axbgkqhv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpsqgsb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnryzts.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2snhlhzrz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkbvgxk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kidllqmr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vddbtqzd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fnanwrzx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqihccg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwgwtrs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2denscaxn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyqwila.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfetxpel.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2izzhlouc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqtimyc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wjunafbc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgruzxro.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zubdfkbs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxrsgfj.html


<!-- 参考信息 -->