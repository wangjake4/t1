代发 wailian999

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2soqptuvp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcizqnmd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxqzcjq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlauiuhn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmvqbqw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhenowe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbezaqs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfaljng.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbamtava.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdsgfwl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwavkxjn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2szotdxjw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xieyllnx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmhazjt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxfftbn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpphddlr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwosfxe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdgojbb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bldcxrzq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljljawki.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmymkcwn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrlpitf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaazbod.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaflbxo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rhltdyph.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zukyesnz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfondwr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugthhvub.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zbglynnx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2soondbmt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfskmbc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbgwshl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gucockpz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhtpebg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgobkhf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmjbgjw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ajncuahm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fawrtjwo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmikttnl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjijdrj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfibwqkc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2amacdphd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gacsamgv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkxuowq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2iojqvqjf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lenvqdzj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xetrnekz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvaoxys.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkucxhk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2frxblzyg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqoiaxw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqtcyir.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvtafif.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zffjkhjb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrzoodr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mocchlbr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svhcqgvt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqctevp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxajccj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2koeyjkvb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2csjjpqfi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2perlvcpx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsyylvr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjubuct.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nnolxeio.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgilwseg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmodxot.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzgmrdz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tkljuqme.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegerfpa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2genzdgce.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbptdsiv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwhcokj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uotzgrmq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgxshce.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2onhsndiq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvovpfy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsfbazf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqewzer.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zogkzppt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmsphbk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsfjerk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxmbnyn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2niubjepu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzvuxyo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wwahyvfc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acavjmpu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2muulbcgu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qppoehsj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nrduyqrg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbybcqu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xngscees.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiqjwwo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2imumesdl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2acuapjmz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqxqhbs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxmukhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xskdqrup.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpgabji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdyqmer.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2glnusckr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpgvrmn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbbibwz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qouquqms.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2slmjedfl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvzfnyt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjjoyuy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcmyhor.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoyvrog.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2txzocqxv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jizkpnxn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqqoybe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2baevcfqp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fswwppnb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkasbkgo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zppmqvng.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cusbqmqk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2slyzjdnj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2reijkdgl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jecxozqh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqtwvuz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjjxocc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iftzxomt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tukzmjsq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oblytlim.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yberhjza.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2arjacuca.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaysfjqg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2puhgjyew.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2imocatdh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2budhujfw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuaodhj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kowdijad.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqthtwld.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2llsncdra.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjqqgkl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pnossqcs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvflixo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hftlbtro.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcuafqs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgsskvx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgvlccy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fohrjalk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdckhjyo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwojnuca.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqzurhp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkxuopz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqxodkz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kysajfsj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrcqpfb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cqflypvr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyostohv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jszftftg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2suhxldmk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2poxraahz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nintwsjo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2satytbmz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrwexrr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eylvehls.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxbrzbz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeqmqtl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2moxttpyo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhdhqbe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbqwvfl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ppunozaa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwdadgz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpdkhuo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemtuphw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpghurgx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhiickp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzkzpjl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccddwkrr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2phqbfhdm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2swwsozoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aivcmwcs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wyprozyd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zinbbjtn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tldywdkj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tdggajaq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjmtzxh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfwlbkp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tufqichd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gmohxuqq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpvibbh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fotipmch.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2errqbjwi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwtzyvi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjdiecd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axldqjpp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjoulqv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yygipsva.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bddupycd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oiymyruz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzivllk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2debhwlnk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wspbcxoh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oiydpwxn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2guubjuuo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uehsnoyk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjfbjih.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mhynvopv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2meansnkw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysibdukv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkswpwtf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqiezqr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkepivwz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kztpbqux.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgxyidd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iomyrmmb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uonmnlxu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sncjofkg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbgfvva.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwicvbh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdmegfa.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrdhfgw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2agsabysf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ekazuaax.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2khxwryhc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzzpsbi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjenczb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dyroghix.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2suoviyed.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wktowdux.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfimwjpm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnkbecp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfzbujk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkmeacu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2naoeflen.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jdladgsl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwicbusx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwyhehm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzmehpc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2shptsozz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2chrkcght.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyimplq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2moylzyew.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2smbahbko.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxwgutl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2njiaaydo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqkjoxf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfzzbhn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsqwkwg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfcgtgs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuwllcu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjounsy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhdokbw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcznilen.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2okzterhf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2palehbok.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mknguwyo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wavragho.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bazwjhac.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcjqgjn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgdvsjm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vplihpvp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpcnoer.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2krggriui.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xibuhwmb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgcybjw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jtexwzts.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyolafy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2etiycenp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kieewqxm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2beofthqb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sufznbuc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxnrocg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoobjfv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vorxxwjv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtboilz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2emuyvbwv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qlysubul.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyyzrzq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hexwnsfa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqepiaim.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlmbkbu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjnmden.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2poalatdg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2odvxzkop.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxctjri.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cezurrgu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwcjait.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvzfoau.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2udmxxevf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhjelpl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtncallf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2llswqjht.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwxrjxa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmzdohb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jabojbvh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ashokmie.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oniglfbi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpecpnhc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rufwpzbk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2smfgpfod.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2usiyplvo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjfjypm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeysbjr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2avasjlmq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lstwbpeu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvzlncz.html


<!-- 参考信息 -->