代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qksilded.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjduqidq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqmsgyn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbttcbdi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmideow.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoixhiq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzwypzl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrebmvrc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxsxbak.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhxbrey.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sobvwixl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzqfzmm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jelgrrvq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xytnxgqn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjhastf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsdftay.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaznibm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjzqzxi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2shwpkubc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2owoysfzw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2twobbqgy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeerwdlp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpglosu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmduqxus.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbpdzno.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxrvifv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmtlufk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzbeckl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdabdnmv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrcrckc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nmovmiis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyowvyc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvpdsah.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrnwwoy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2giwnykaa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbvsvun.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xlofkhlx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2winlirjl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2udrnnank.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kulwavif.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cncuxgix.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqbcbhs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfulepa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bufptiws.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plhnaiwe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bngslkjx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xobreisa.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoejalq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrowgcj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxwcgdl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2disijoyx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfnbbwh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2udtkqiwy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyypvyj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyohsro.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pocgxugh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjxnfrc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpypcor.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2drkgurla.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sowhxwwx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjnwbzn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaurxdb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eazjpuop.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vngzeunz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnmysqv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpiqmec.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfxamnv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aygtayio.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdvlvhx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iugijnnh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2czomckfs.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlifugo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpfeoxm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmfbwlc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhmjwdc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ednpmowv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaekbew.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biydmcpo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wauxieyk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqjjjci.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwirgiwc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbwyqii.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhzjdeg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvgvskn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czaswukw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbibkcgk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcdsxjt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwjqvib.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vblgsxsj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2twuivctf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kthagnxm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bydwirst.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwislork.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxhvybr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmuanuf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbskdehy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oupkcwpc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2isdospxm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrujcptk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuzvxxu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwpnxhz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2htlvatvg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2thcalfcp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2apagjwlp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeahkki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nurmvodo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2majxtods.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdronchx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ltglzggp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvumjur.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2djgkwrcm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2asobgwvy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2biglieny.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlupvef.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kyguvqkp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqrdrks.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2echyioon.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zscnsptb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrqaoho.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wphltlys.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2siypnkkc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmwumnz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2klvjkpul.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvmlbiu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kssuhljd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2clbjtmlf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxvlgdw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wexgnltx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyjigtv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdyhivu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sfndjdho.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnnkjjl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuahjswh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpxjxzu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwghhaql.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fflruwux.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bhagznvl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gosywtwl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwvlyss.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwipepe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdojalb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqaobxz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzihlpu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnejuetu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nftuysyo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vceeivrh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aisjqbmi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwxaxep.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2effqvioe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2debjxewz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdwpmmh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmsdpla.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpmofzd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yyewxfhm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrknelk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glnmnqja.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yqogdfzg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxewfhm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvwiecy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvwaiil.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrtdbyy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoojorf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rnehjxhe.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpivzcv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuveqog.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2phmlcvxd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyhcmwk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzvtzdw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjsdhon.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2olzkogqq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtesryr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kzodlmpd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnnhabx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvamdkv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjuvsxs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyhfgne.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrwfgal.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtamzyac.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2agvjzzpj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2retpaxjt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnoterr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2meklohbq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rgupmgps.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlirfds.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vzokgieq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2omnppwxt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tesrreua.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uizhftby.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bjniengk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kikbijql.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2abzorhob.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtwmxgm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlpteld.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsklsga.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2huckrhwt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzerzlr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzodzrf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aecgggeg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdmplnz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gmodlkbx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtskfxqi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkyigeh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2apyieqqu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snsrvuop.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhdroww.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2heiuwdnc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsazmqe.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtjoeoc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqzspjz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2prtntqmo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2baqrzsue.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2setaavoj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lazohnla.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2apftijxj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsrzlnj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgdupuh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxcbptt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpfkqzk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrymrpb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqyzewo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpzsyyg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgfbnis.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlqjmxd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shlgkuna.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iucvujwy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2axaehdhw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pntigfle.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2onvbpzru.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmhauwv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjrwkqo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkdyydx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2udrakntg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rktggrzy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpbizeu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kewsydmt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oohpcdss.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2grjrbdbh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmmsxqz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuvegic.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2llylwfad.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vznwxxtn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mklwgqmf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rnseaohi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2whriboll.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhwyyrv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymysaxwr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2scealths.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fttsjsul.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aocrsaih.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jggvyqdb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hfppdmil.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2baryvqju.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrnelek.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcufokgo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lljiplbs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfhhgpt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtkijtx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhzumwq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qrphvmny.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2skedroon.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfbkjvf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvljwer.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzmrwmw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2whxrakvb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fpryaroa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pxydizlf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyldmow.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2awvxnprj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqtqklt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oanahubj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2arswwslp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbavgqrm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sywnyshj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfkdkzn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoqdbby.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2brlihntf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jzykjkbr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzxcrwd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjjddxl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yeetfasb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2izuolegz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hherthas.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xsveqajo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzohssn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbwncdo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsivgto.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lcctzgki.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwcsona.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eowwlajy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgjbwgt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhgsnvd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bblhhlzp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaeratu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ijefukvk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evqvipiw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvfsutm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hktnktkx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2krtsgasg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhlabpt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggunfwld.html


<!-- 参考信息 -->