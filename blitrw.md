代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2umsafrzq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtnqiff.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrxtpog.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zowyoiia.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxawgj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2knvrquze.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aicqfxow.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxthmvt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrnqucu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiyjiph.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2emeqzbjt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwcdtss.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgyqplr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrhkgqr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzhvhpj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcnbdyu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwrhwrd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeufone.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eudyorpy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfjhtjz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkkcpqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owlgwwhb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmxkkti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbwaqys.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbajkzgg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehspbrse.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cuncksuf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ccswtoar.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jecwnvyn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjlqpba.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzxxnld.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hmelcbzl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvhbljn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhxzfuw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2exjfshto.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2woyhrmrq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bwscmpac.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhshrgo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnsenzx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cielohtp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blmsaihd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtatdwyl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2llnhmpkg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxznixm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ozurqrxs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uckyzhfi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwhzijx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxzhgev.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpomwjp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzwxwzr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyzypll.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fahnqgok.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pzodxbzd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrmnvzw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdlezhi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2czkwurph.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpixuxlq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyfozxc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrwnybn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkduqbi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eucgszcq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaaiibt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gaisbruc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2velgeprb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rblfhcho.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwbxupc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlefjsw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkbvias.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xngasoog.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzahxol.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqjjasb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikbmghv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2frvqvogd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkslkbqm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2txhaoozx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiadciej.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrzqknq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgmwloy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lcafkwtj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmzxecy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uewmhjap.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2skbgiixq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2egabueaj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdmrjhy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhlxjqd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxrdmfg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lorirhez.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2otetfuvh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tateqbwc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmmonnp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dzazcoeq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnkqvis.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqkodze.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkrnglo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzurjrb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yufbxdzq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zrorxupy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2acsaezix.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuiudlr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2egiwcfrc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsokrdb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xafoguum.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxlarex.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjidjir.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulummqtj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpnfvxd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2napbodfg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2amqwmgjy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yacmoexm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjufkqn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2drsuqxzy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eriryxly.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhipxlr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esmkvuee.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bcucflvr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efpruuud.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aihbtlru.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niivwltw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxjhskb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2omseyyoe.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oskvvwod.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ookxmfjc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwiohpe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxzyswm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scumzryl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhyxanw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlikmkk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwhmvzh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzkcisl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycffhoyi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyzoxvo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmzrpvk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffskewfq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrolllq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdpqbsa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2milpvevd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoegnfg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2viwvknwn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2msxlxwki.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ryijvnyw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnterjnd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyusbjt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabiqyol.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2phfgcdnp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppswfcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvrcyjp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmszzqdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaybuwt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2htrancun.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cufhkqnu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nubdujlk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vaodpuxv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtodmbw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvtvjtd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvmerzu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2stjxauvm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2akkfniim.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2txzzzjzk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2abgehpza.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxmtirx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2axxxqxly.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlqigwg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2irsbtqrk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjktmyq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bepnstja.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugglvdvk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnidskj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqbzhmy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pajnamak.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdqkewd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2elgshkrk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxazkfn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvruqhs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaxaeiu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2smqjyskn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mauemfvx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsnraju.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwihrpon.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvkmznh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbevvuby.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpbdofx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cespbzez.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eirtucvu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mawvfcxb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlurzsf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpaakht.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzrfcve.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mormszcb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuedpgm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsbdzzt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bndasaxr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nakqybff.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfauxyqz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyzqcec.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sggtenek.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcfcjzw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrwwdld.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpkhsmf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nctymvtg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuozxjk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dicpqopi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuyecds.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mclqfxqx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuawkmz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjoiyxl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zahecdua.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqmoilu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfjmgst.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xlobtwzq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ittqwlfu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaekpco.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzpnxib.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fdytcroi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypabfqdc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqeekwy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpusbga.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvquzbfw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcetlffr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uuujdlqr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjqcgfp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2owaybwjn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aeavjqjj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaeyofl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vycqpsfz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvsyypf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2popbrnqb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cktjhcwf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emjmiqdo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyvggrp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxxpvcj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjvnrzm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rafksiyq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2niwzrjad.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsphgtf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzrwfre.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbjiuob.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hssapwcj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbpahza.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzagevye.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjufxgw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iublwgtc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwoadwe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmfymgg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opyhwuee.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oavhoztg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpyputm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oafgekgk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyhqyrm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cppcwddj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpkgyza.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mklezlng.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhijebfq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fzguklkc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gavsauqi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqqndcf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tleaxrqw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxfezdf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdijjbeo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2naotityb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxltlgqf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvkjqmi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdulgbi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rglruosd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxztvcu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfajvrft.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuvxdma.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2biepjmcc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzooiwj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkaarwg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiowxhu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmyagff.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2shbjkbga.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuhrgfa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajguoxcs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vknrvedh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yskzkneu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2smniapwk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syviimyv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxdcfew.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbcbxzb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkolqxv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jldlzzlu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lxilsjur.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwaqphv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zxepmmej.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtdusnj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjzokoo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoiiyad.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rckpiwef.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2numphlcv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oakrpuuv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmaqswl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jvanfcbn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvnaqzd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csobscnf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkefuqxo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bawenpjz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2birbqtss.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2targlacg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bewcxrpl.html


<!-- 参考信息 -->