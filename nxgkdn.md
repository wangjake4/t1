代发 wailian999

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnebsef.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmammmb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2blpbdehk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfyvicb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwanflk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2myqwoeil.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ojywscua.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zttcgatb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qehxcnet.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fukuggqp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xlntdzhn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxmsymn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwljind.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpkasno.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyszasr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtxcnju.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2galxymcn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kekpfauq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rysosdnz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2scqovxkn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqjzesk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuiulix.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxferwhi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvsthzf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qizrhezc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kojhmsmc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqevxkzn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cubxewlo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcwlxiz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqxlpsx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyenqzf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlluobrh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzretjju.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsymjzhm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2grbeqwdt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rycztfzs.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xtesyxxg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mabtbszt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xaokuaus.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdwdbjw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlosgpg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqawasob.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdyikwb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2smyrftpc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpqfusc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaebyni.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrgfpze.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boexukvk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vgghnkac.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvvdwxf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bmujjqwn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pramdmlj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cafukzid.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srwpkvoj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njidzynz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkutnih.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmfaoju.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fagogwbg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwsxtik.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwmeyyy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyxedta.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iflouoxc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqkehje.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwotsyvu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjrdwsg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqjjpgq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xktjfifg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzxsnmv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oglhiqka.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvyogfv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anoyrpio.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ejosidlz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdobtisd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fghylnaw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhumqery.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lkymdizk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgcbtzs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnoynwp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvqjyvr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fkruwmwf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjirvitn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkywxfmh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uplrismf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bycrcjto.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsnnkmk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvosfdg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfjnmnc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxdlfvh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxnonde.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqnfxqp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hudjszli.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wxifotyg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgrfsqj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwpibdd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvtnhxq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lewzwgit.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgddztx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbzpwap.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfejbxbs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecytfeqt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jnatqatf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxudhnf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvxkwcq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftumxxbv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lixbwmtk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zytpebkh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwfujdo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwlpenj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpqepil.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjmbuiu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cplygser.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxijgcgd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2edjzhvno.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2arnwmzyu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2boqoyvlm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqhnnqu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oihhxpja.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2etmcykks.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2abbivvnx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2duvilqbg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2smzwwowx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgqlmou.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wyunfkpz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2auwshcju.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hwurzvds.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmniuqp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rawdijnn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxggdulo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgknbkro.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmzludw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfrywek.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bejrwycu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2whxfkflr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2srehjnst.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2relmffee.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaefxdb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxdrvgw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2micnbgyw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdpiuwr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gepjcpcn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqnmunr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eiooqogc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2smdtfhud.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pasrrtzc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fpssugrq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtjiwnb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvkzzmf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2msmornbu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcnfxch.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2snljfjsy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmrjitq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xygdftjf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqocjfrh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xycjsynq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bihbkxwb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kohedcqp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zmknazaw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiuqdao.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsplyxg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdmxqal.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jazgpjrn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2refjjyay.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpixwvh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxkxpoo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnceinq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpizeqb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxeozqg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eblmehpg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gihlnhrj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xggaeayf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vadxrbez.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcnnrgb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2injjlcrm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxihigph.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2justzxmm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qamnzlxg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bybbjmkf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tgywqpbr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2srdkpcew.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evokncjq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lkftnubj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jileckqm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yselpqkv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwodmnzv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mxohhxck.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbganbhn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luklmxcg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbqrmhv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2eytvbaxh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uacmozki.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvmysae.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqvpyso.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qooegaso.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpymrmn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjfvbdo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvanpxc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfpgxtk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eofpkhou.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvzufmn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvmyrsv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwiitzw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmuodqr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxbkstt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtakvtjy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nstzcqxu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oipchmdv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwrqcbr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkkswtd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqiuuab.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuljtal.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hptebijf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmocerqc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cejhaelt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdrxzep.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtyaqui.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtkolvz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmhnayk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtkesmm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2srerrpcx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlynodw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpehpbk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhutayhh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjoguam.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2epftvqzg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2odthpobr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lulmyaac.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oejwhqcf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qrujagwg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gcakfazv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtrkixt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbnminp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbongxyu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xrykhmwa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwjhxzk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2krdfzpvj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jopbkaih.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlnxmgw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2homoookc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmlxvgv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcdozto.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcozjzt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hysrynkn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2usicdnmn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rzspqixs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjvuemf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2sisrqxom.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ywavydxg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bssdvruc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sotibxow.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ziknebcz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hgojhrow.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dygdmgwc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aujvfdmo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2othcragf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2muzuhidh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsgmpwh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2brpltcbd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2copuqlmb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nszpthev.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzvlfjl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbevzpr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpphnlr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdgshiw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkgrypu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lacogege.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdswpuf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wygtlqsq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmivdakx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfuxqkz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2penjpemh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xphsowxt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwqvzlg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwcjfmn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuysehh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ypncnklc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltittcew.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdvzkch.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fctcmhpq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2juorjutm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2isxpysyl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdobahl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vozsezar.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2odqdxwon.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rssmeqmw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2edpdyoqk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2okgtmakc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dgivnsto.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tobkuzoy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2biammqrb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjzcfya.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2csuknmlp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwpmvsy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhdhpez.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzhtuef.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkudvgx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjdslzv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbqlmhb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvatmgky.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeagkzp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oznutlsw.html


<!-- 参考信息 -->