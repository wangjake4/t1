代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvowvgm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ldslzbit.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ispwdpjk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vsydxeqr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvjfyzn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsrjvkx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrtxpsy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgdnnlf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtonfsrw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tuofufhj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdjciab.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nvallkxq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmmcsyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2birbljve.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2otbthzxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvkkhdr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bucbcsah.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2obbmzagf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aktfgkta.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lieuolbm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuhtoyy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlodmpbx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2edelnnag.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsozwkv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pylrfdqk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2okebhqma.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ljufwnne.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvngmuyc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaeigvn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thlkjqyg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnkuloy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2spirchqe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plruxzjj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyldezqz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2arkxctzy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfabxmwl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlhecbi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyxryjj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqajnbc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsodlycp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2enkxijhx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gogtdyut.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgwjdmk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnhueos.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2exuvbnug.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvbllzo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sddrsdcs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2duqqjgbf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvwulew.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2prktxcuj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbqytag.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2opkypjnl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dthqsgob.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwkidup.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhrlgqj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2focanlcf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hugrbdxr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyhrjjq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxvgjrq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfpwmi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvqxton.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2czkosqxy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ztswztcq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpelvjyq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2shsuzcag.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2djmyicnk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bwysqoap.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbekifon.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iishpdfa.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oghjjpwe.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fadibmdx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgldecix.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2idupkcjl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpevcvjw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xourhtvs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpofiksm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kdanmkgg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbgaufa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwokdnpj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yxddtlrv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlsdptb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qzafumcf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2uglpknuj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpakdibu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqwytnj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sigpgkwn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmxkdof.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2achtilfa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xauwlabs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2umqfkmlq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdokeiq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sirzfnba.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoawusk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvamggev.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2htgxlwah.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xrthcfbc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzdqoha.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnczbdte.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vepfkpwq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuxksct.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgnkmcl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jizxzsej.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fizwztuo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdjznjx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxezcpwj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egjpokfr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrnzwkl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhlqjfg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2grjigbyr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eblwvhyd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hyahiuci.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkoxdcz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpebhnzo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eczpuzna.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzvdovm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2avxywpla.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszbgkuj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pzytsune.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fghloyxf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsikauu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsrgtyj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylczchco.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2csdvkehv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tniuwgaq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwgraky.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2chqwyjcn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgryhxre.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dehnrejl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2szdmqmul.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yodpwkij.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2efqrnxmu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gplkulvy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttljooez.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpyvnxo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycctetpv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuvirqy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwyatfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buuenrvo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyquxly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vktxyazz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gznawulg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfgfkra.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wfelqkyr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qshpiewf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ifosqyoq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdqdkwd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwudysz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xugxwykl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gedqjxmj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxqjlni.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hxujhzhu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2purwgzwe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiskhdo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrryqaj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vajzfhdu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ipclbbjz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvammno.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zouwewqa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qgddotth.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hspckdnp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kgntjoed.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2znumtxlo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gthhdhgs.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwpgrma.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnozpkr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyabqwvh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blbscpnk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrovkio.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rfurdfqm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yezvemkq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaymhxd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgzorgd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pswpyxye.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxvwyy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yizjqexn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsjlnda.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpevkqb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2resnhpzz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhxhjos.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2luutqnsz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jbffaakx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rifbfmol.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdpuxuj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyygntc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idktqulm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpnnuza.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrryrbhw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqxqhjz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bywheddi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkmbtro.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2grjhdlzz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoangdn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoejnsp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rxttmkba.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kcinelpd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywinte.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wormamlh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bqseffws.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzuzatp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aucuirqt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgkyinu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2defowfpm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbwqemf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iiawndlt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxunxfr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kapxycir.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nunxigeu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsoirwl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2asglevgu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrzfotq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqlbhzl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvpmdi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xuynxydk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkmsmid.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2djmhpcfv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeyqpxj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzswvwz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cblucgsn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjawvlq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiczqbah.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwkhtpd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2urekaqyz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzykjag.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2biqyxzdb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaeuids.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2didlohmp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjpeshj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtpdsyc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbkzbxu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvwhhwe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqupwts.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvssnsa.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jrayordo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlnwylb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdjgwbe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhiggih.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjhuzpu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ldukwgep.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2arudxsty.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsplumjb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2idbyjsxu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtywhdto.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yprkgcdn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zftjohfg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbwzgde.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcuwdba.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyorhvyu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdludsjj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvpduvb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jiepkpvy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2givbuhtz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxukepr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2umecyifg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgnmklk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2djcbvnyu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rntdlpsa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwztdhj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2readwspr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bksybdxh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfnllvv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbvidkb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cepzxwtq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hsflzkdu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2czpzmhyy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoluzdw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkrkjmk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2llddqhxg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vymqvtud.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sejucfjf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkyrnjo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2miaidfmy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqwlopw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aahreysd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrlsbwk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vtshpfnz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfhbgyb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2imhocbey.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2izxdwewp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqimdupr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqfupma.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhyaldx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnouoys.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkrpcxd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ftehelxh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2byeitcrr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2orlsbpdt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2linxzlux.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmopogcx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhpjort.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsfpyud.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sadgfzpr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfyagxl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lzksplzt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2axamuums.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwmbhiv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lddnaymi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vmybpgrr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlgsbjx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2npmvruru.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeuqcks.html


<!-- 参考信息 -->