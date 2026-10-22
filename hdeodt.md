代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2equzgwbe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqxackg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcsnzsp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkejorp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfihmam.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bektjwed.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuyptrm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mjungfxm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2salcvdsm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aklkiqxe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2btvcsqek.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnfprpf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkivbncv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvjdvcx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeqxqll.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyyeudj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeihlfq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2erhdluyp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2viurrsqh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qcilrlaf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoxbtaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urwktxww.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxockmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfvyuua.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxazihv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfeffly.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mctkbouv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuulsjj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdrbium.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyjfcbz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ergpdpoi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjfetyg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2owscmvva.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hszezgxt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kelgijil.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nspvmvav.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfbxzzu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sepmjqmm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxklhvy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkttnns.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frcqvqar.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxxgahx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2itqexnmt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqibmhxz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rigmkpxg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkchxsp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mznexfte.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nicfqgcr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpxmkqk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuaasbf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuetvpt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxynefo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzpdtnd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoytdmj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnsytsa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdynneby.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aloumxld.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzzyjzt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhidibvi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuunaqd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ybszedtn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsrwjxn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqhbatb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsylnbb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhuishg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxprvgod.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxaaljr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acxwfwqf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqieseg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eduttogi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuitbgj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azhycbac.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkepibv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvyccoz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgncvvi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwrmzhx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrympmq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2biednkhw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvcpfvo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnoyvuy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbwewnr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oirrqtob.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cigctysu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2acwagmof.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxbhhgp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeaulex.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obgjpjms.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sriicmdu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdojtxd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmeoldf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrbgygp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmjlmxl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kslkmrrp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ashycrll.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puswitgm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqzfdcx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjsmivg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2njlujgga.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpbuptl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypymwktj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dkniieih.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fitgtppn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gobmbxlg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgzibai.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtebjsg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2swwnjbuv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svypxxtl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeotiahg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqsiupe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vslcfvgq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aolfldyh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkpytkt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xpunxswj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiotvixx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwwprcs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2basjhiua.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2slohdboi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkrjlar.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iariarhv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdnkziy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeikvnal.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjqudvp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugptdmql.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ricziuwj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxprnmkk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeehhfd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwldznb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqtnhtv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbrmfay.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2popjqsqw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnslcqpd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxsdvkq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bikdxhev.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xcepexqr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2srysfhju.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhdvwhb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2attvttni.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jeabibtc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieymnerd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgraznvq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hshzyymj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2krztleaf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oslpaaid.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyivfwf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmpuhxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrhnqqc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxmvqcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtemzvoy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpgiijx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cisttfrw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbltvjg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qprhkumn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmahbii.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2powehcob.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hddmabfn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeclxgd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpznxfmw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsasgfji.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyrrnnh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcgbhoe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aemszbeg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzvarli.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpgignu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2eodwclob.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xqihsvur.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2afvnjsyt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2utiggjgy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2grfbixvp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfyokax.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcodbgzo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tayyedvb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclchohm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2csuufraq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogatpxcc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2actjcppq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfjzset.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrmtpkd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbcfbkh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2caxnsuvs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvucdrz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrmuial.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcnlwgo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgamozl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiyhtqr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqsargs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaevbuaw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wybtpaks.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwrmpzt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jihzwupd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsuceoj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgxgeba.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwztthqt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcaxily.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eohocmzn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqcrwfq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2spjaozqs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lafsybuk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmdbvdk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2imkjxfzd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxwcipg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2adtmquyi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2irxhniry.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kfymwqme.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qipbpjqa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlahxho.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvlmrap.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpvahwl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2biritdck.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2etfqxrkb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeiqane.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzxnpne.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzlklil.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gehqjbau.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nltwnxws.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gofgkoeb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgznkql.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eotjunfz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovboaedi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tigdrjoh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzqfvda.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2onpjiesk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmeviaq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvhqvkc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcxzjzm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2enkffnmz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2swhetjkt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgxphra.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpktnrhk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlazhtj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdksnkz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlwauif.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgucgoyq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdqmlau.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaupxns.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxpdlnu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtvwarz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2papagays.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gseawrus.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kfebsyfr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mhikovds.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvajynyu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmlldmz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2enfqqzta.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxalyep.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmobmpm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dktdhzfj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxztcgs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzahlziu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmlfwqu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywikqkqs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hypaymqd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqxqiwj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjzpfmk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmnyjmw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrvidfy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuwvssq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ygunctbl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaqsytp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiojxzy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqrbvyh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzgzrzg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2poldsxty.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhgtfjo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2demzfpyg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoxchbe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcjevpy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2onyxghbm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2znxgzrqp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2elikzwga.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eussgxzb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2upxhtsxz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyhnefu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aalzyynw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbjjxco.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jlouwgwl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrauuog.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgelkye.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2agxwqokj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmvisqf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkxifzp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbbgnyx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nenrkjer.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwqxacp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cytjfwbw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yznztibm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dakhctyw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2exybvihk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdypiavn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsumvfk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdwyuew.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2veslqdko.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cwntteqf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nphcxryd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqslizp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpcumze.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhwpici.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2deuoujyt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdytpha.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjrwrva.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcqwrrd.html


<!-- 参考信息 -->