代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbwhqnb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2suyeajhs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cstandxn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjajtpl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcymcnd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eoypxvub.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhxkuwd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qavuepiz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbykhgbi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kibineyv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyckuewq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfnyvye.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsddvssx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2efpepubi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyksytmj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmehvaw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxjzrbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwqnuiz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpdgufn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fduavgbd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2luwjabta.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiplkos.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhssphj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bvallzzc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fzezxwmt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hstzrssi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wplnflki.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nuynjchy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjhwram.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xedzbpaz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2airyhvni.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxztgplb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkknyxv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqvyiid.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmolmsii.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkurzcn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojomwjgu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnfghsf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsdkpdz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2afkwjalo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ochqpehl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2naazqzvf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqjkfmg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfaxksi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbzsptq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxkerqx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkenmkh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqvcdeo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkcjefx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlgfyrq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oydckukl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmfsaho.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyekusz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2woisvnkw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2acbbamlr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hezpwnqg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qijgtfsa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efghgxij.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrbhiwz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnvzysq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sontyymy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2auyriohx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2axmshwgq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2porrlrer.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mguekzio.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2quwxiyab.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgfxebp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvgvmmn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aiorfqtr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjwbmhh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mwybvqxg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoxfgfa.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2btcvceft.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvldkrw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ngymrals.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhmuuva.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbpwbuy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqthpjj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kupxslgn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvvqqnd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcaeygi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhwgyut.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjpfrbz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sahebduc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzybrvcr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdbxoek.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtjnzxm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqspsjk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjyeazo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfpsuaa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfreitcu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nopxxfqj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2honmykai.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2okyhnqin.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnzamot.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwpfggn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuvuapb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxdweuq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdngnrw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwlknib.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgkojen.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwohnzx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yzambtrk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkjirnn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpgenkb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkexito.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfglhsp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imdyqgbp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aaztzoku.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlglknfm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2quigivcn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhamqbc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vrogttay.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlejhyni.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2onghokza.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsxutiz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2viepnbpl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vafsehsn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgqfaua.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2irbrdrnr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrlezme.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2puifelcs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpumuyh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyvoidi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nquvhazr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctadudjl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rprbkjyl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsbzxzc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpmxkns.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwwetfh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oknusdww.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbnqxmo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qidarcva.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2urblfjvy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvmxrif.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jwctxeeg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwfhhxs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2btrrmhpy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifzwbja.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tcelsjzm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2giaesfag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqogqcd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvfbbyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txpviqag.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrnvonn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbfswoa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2momxmura.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwombdrw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzzdjhw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oonhqvol.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2coouelra.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcttves.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2smhmdipk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2edbkkqwt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjfjyfm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyciiqs.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpqvunr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pggpdoje.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuxwplf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsukamd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwycoyk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2iikbafoq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhwqxfm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbrjvtp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmyoecv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyeviqc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjimihg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxylhhb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rffuyydm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhyzkrx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxfwgmr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2onvdyina.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dbopfefz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzidtfcp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2thpkxwle.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyffeera.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2biiypvmb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmeyatu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvockhw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzimexn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvocjlw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhxyjjl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fisuqtsx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltbtnuo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrzaxnb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxknjui.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bolgiqyw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyihivfv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsmacie.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gywqpceb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qtheyrvp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rswhetfp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaljqso.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpfedgu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mhobyfzq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlnstpq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2blxhpgma.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2orbiiymg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhsjmdt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ceffxtuy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgbzawq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aukcbihx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaiqdyk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvqqbfu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyypdjo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2egnzjzmm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvpljlk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2montfiuk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtysxzk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rottuvot.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtkhwgd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpwalir.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpgswhp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oitghkys.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkjffzz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ircxuaml.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxhzuqd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xywvqobb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyzfmrx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bxncfbwr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrejawo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaykpsh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zupoqxns.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxieyzq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tyycmvsp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bcavkmyh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpgeaew.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsgqdxa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrdicsd.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2yymsiihi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adoecvkn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2anyapyqh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aepcittu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imxgbrwe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grcxekzy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mctzvces.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvsxxqj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoabrxb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkvsvpl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pppjtcpf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrljfrx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nddidlhz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpizpnj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plbmicib.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2celybyqa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaklcywh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrpmves.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2utqxbgmo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2msbddmzt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nifmntpj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2prqplpnb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhjhzgr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeqlpse.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jratbwew.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyowyqg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgoeyiq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrnbvup.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2urqgwrsj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdygcqd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbzvdrl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtoqemk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2exutlhkw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdselbbl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tozukdkf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2upwxxqpk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cppwuiio.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pnezezal.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkdkskr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrzzrmk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2apgquzio.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hykomrlt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsvgkvk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxgzezc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgebbfuf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdqdjja.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2blzokqpe.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaycutd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsrsksy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xkawehjl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2henwubwh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtsvnpe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlesxkog.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjrspok.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfplgamp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2heuveftm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qejvukgg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkswxph.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2julmcdqq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrawaba.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkgxibf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdmyjqq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2agasxoew.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzbtcbz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2esgolzly.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqkxdbx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmsfgby.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jlehfudm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2scupquud.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2faidwtcf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrpusas.html


<!-- 参考信息 -->