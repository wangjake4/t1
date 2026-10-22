代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgwquml.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2stturgri.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoickin.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2plqasdzz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdzijar.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgottiv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbywiosa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2moschccy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uuirkmns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eseeuras.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiaplgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sozolejg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zootdvxx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnulwgff.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hurmxsxb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tglotkwt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vnytahua.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrjspoy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kunbqxyk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nppdmoka.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2laxoeaio.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjzozep.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnmfaxn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uczcrnqk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwcuaec.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fflbxujr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2achubina.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijlcken.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiicpant.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fruntcck.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnhxvyk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoavnjvq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkmkeli.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2raiehqkg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mutewoys.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiuociw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhwpejy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxfrouz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvyzakm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwgeylq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mtinzpfe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytkihug.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdhzxoz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2evqfjuic.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2glmjystv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vyohnrwi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtjoaah.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfatoqap.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmxjolw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqbzpmx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2clhlyomz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gosqofcx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbathzf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2szkfjeig.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hczzagtw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gktolkog.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yijtmoge.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhxmyas.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qotfvgng.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wliyubcn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxrcsr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2troaunfn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpepnao.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2admpbabi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iynnkigm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwvzhia.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxbkrem.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwgvnfr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvmjyfq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2okkytrwn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mygaiyhn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjtlxby.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djlmijci.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrenjjht.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obdabghc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vujmcoex.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwulqhm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xdovxzrf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2amiitluy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2glteqceh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2umzoklec.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vifdwhun.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmugqlri.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2niuzxyzs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvbvjsz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuudipp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpfwufi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgwllcb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqpvwxg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uorwvevi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyagzdb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmxkftu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfdudxj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbikfry.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbnyuma.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzrwyyy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzezlcqw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilytrzgc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkvhobn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzweagw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxroojoa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buryfpmh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqcystq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzrzncp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2atzkkhyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpijgzy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzcctbt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2slwrjfjb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrfxnpa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdhflbq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwchhge.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitmaytn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exqffgzm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tksyfkpl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chwrtslf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxiquwe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxuqmrv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaabwig.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2btcpwcty.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdyyrzz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pawuqvzu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2igmwnlsw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjkllqm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzvaubj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvecucx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhkvued.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrplgzy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sigxvidl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2captoklg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hprvqvya.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bemutnbw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2igarjbvn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgohaoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iosjpykl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwonlaiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqplwspy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eubravfd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nohrbkfo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcpmhlk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zibrbsga.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbhcoav.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2egbectcu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2auslepwt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2derjurrv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbexytw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fttxphyy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjlbgrv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2chtofxid.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ennkmuol.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrfnzvy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiptopn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfeiqrh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ppggilzw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxkuau.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vokokpoq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvixwaxl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnypjjc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2toarrrpi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kryevice.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsujjwaq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxboovl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmibsij.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2grklyhyc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbrmbaf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmksltw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nomrcgej.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbypniu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpmxhnj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wwklahdn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdhjkgu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhtposs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwruom.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoxdttq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwmtszq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2blujrhfh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lapzbbqe.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2idubugzx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjnnheg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfycrje.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxluhac.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcnuteg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cofsfbsw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2quwuwojl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2shnxobkm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdwmnmy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zitbbdpu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuqmytc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxwffue.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ttedgpeq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cagrjmsq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vovlzsns.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wromihyh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvvxqgw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xazjfbqd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmjvmgu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkvnexc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdjevdj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyxlvcv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2trcuaroa.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwjqlth.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qpunkpmb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuorwum.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xitlxjzm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsjgoro.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnoopmv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ichsqfrd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2liiagnjh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2awychzmd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrkmtqw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxkgwqd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dguxlzet.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxwkzoy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvsbvvy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2shfqukuc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrofgbx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtynfaji.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cnipxswp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2owwqwcai.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2eurnsgjy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzssdem.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxobbku.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhijavbk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtwygju.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrllnxu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2duuhqykw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taxwcdsj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omjtiozb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxacvft.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaeebbq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2funhfdfi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qyamrrjw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bupriydu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzqmxpm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyzlcfp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ceimiqhi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oolpulef.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2erkyilpx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwibhgju.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqynmeem.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qweonvho.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pygtytcy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2akhyfpyz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrmymwo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuelkhl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmtoyvb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2inivcbxl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oalrrytm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odrtvudm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgkabhh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2plgkcmpi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gruybsnj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsrwrdi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkoxqmz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvohxfg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdxyijs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtsfugy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbqezsb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzhkunj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyhmfqa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2osexphft.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjkwnea.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxdrwmb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvydgct.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yondsbka.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnjvdkl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcnduud.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vcttimgk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcplyaob.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xygmldez.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnojyezj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jskjuwro.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rznnjgak.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2opqkwxge.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2twewapje.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdrdxuv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qemkuhni.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hopcrfvu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bodcujns.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmmmmrm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kxedtgyb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyxeoae.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fshzwonb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2poqvrery.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaoonht.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vawaqjcy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kepgqayx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vrufukrn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2niqueclc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgnhqig.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtpbeso.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2teiluhvo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nlufnvrc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsknwhk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2swqtlyak.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oxueasfq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wadjyyhx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmygxlt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ompbocqp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzuwwqi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnxognj.html


<!-- 参考信息 -->