代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zeybfffb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkdewvw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxowhhh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taswkqxm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gzymgbvm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwaekvn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnvhyvt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izveqhvs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkcamkb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imeqolqj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fysuizso.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahevuzwx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2svgavbxx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtegngs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2olkntqyt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoxhvoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlihegr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksugzzgy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfgzcmm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2crqfntgz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlbfxyx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mryjufuy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywghtlhq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jldtkxwh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpwbmbl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtwtojj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdmgcoy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmdmzhh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljctooye.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwnvtcb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxroldj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kamnkrco.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rarrulwp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rgioozmr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnugryi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkhcnab.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqrgfbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lekdokwh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uofsjcpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmxrkyf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kdarwrwl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sansujkp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtmbvtr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkpdtax.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxzssmg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yppzastz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2knqhyuct.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kptkdqyb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdqcckb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdkmxfu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2larrxfkq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhkxopf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bkikrvld.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoggego.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwigvwz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nijbqalq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkkujlc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwkvgau.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2notefmwk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajixkoqd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyiyuir.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsystrn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2idcdgsms.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawkyjuk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdlsgxp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amkaovkm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrnngux.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzwmwqk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vojlbwbf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvysdoqd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmyxnmk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwvwkfa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xteouprx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoldvly.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbpersk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnncwtuw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aevwfeds.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blznjqch.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzvfzcy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsyvwhe.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrqdmmv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihjqqro.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oblntwzn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzqhhoi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgntorvn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2etwnyaof.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kguzelvj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2halbaoub.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhdiggx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkqbdnq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vquxcznt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylanakrt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqmfraz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoustlsc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ufszjoqa.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcflixxs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvjrmbo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2otypwhzv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqhhfot.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtiurba.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iezeazvd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjboqime.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmhborf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwjldcc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeflkqo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pgamnbwj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2obdjkrve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbaewju.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwrmxxa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxefwnuo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfuwygs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrixvkm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nynkfhje.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlparibj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqzpsrj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkvcjrd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmryjrn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2imkrwond.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbsffrx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdbronp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owbcasqm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2avzssbij.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjtuywu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cduhivwi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aazopvhh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkavgayd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rybiygeb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byenmgko.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vcypsfst.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdyhswk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2awzntbcu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqxzfsl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtgsmug.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhgtsaq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtgrajo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2itbqkgig.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfagesjx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sehsenox.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjlzbbu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2usyvbqmm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsevsaxd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkxtgql.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tejqbqkg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vihrthhn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkqdpjc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhnlysg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlrmylz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgvezwk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiwaghx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vahewzvm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfwbeyg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tijuqfsj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2affojbiz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2euxqfibz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yytcqnyk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qradkdtl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqvqvop.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsitjrr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijhtrvc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rstlmovc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cthozbrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxuvexh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcamyetb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoogrkci.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qexgqpse.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzhltpc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwlucsj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxbinlx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2urzfbnra.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhwktey.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxsdbyp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tbezrerc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoufhzn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbilblx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tweamxrr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhgtkfk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhukwai.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2eepfogii.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxsfzzd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrknbra.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjzezlw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eklrajie.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fwasuyfb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiphzra.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkcosjx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjdfsqf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjdmotc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxymucx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krhxszks.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkplcjni.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxzztea.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywmffqw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjxwwge.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilinyrwv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fjaegcwm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jozdhjds.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfjviki.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jagbexjf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lzipjdol.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2chjyhtmr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmviolx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpkuwwu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ypehwtzx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpghheav.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjmbdfx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvuryar.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2malzmvor.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrcimel.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeuxahl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mafgofnt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkmcgyx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjgixht.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyeoxmo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fakkgyku.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2igvjdset.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkestar.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzpoblu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnwjpdl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtiwmep.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrzrprp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrtpkhl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wljxmfpo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqnpvzk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnnuakw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyabmri.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tzslpqcq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqszhddw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wymcjzbo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwcrkgb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2uziieoom.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2agpecuql.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2biccpmbo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxfpoac.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzchjhiq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyqjmdb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2amhznigj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qehmxyhu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2szzlmuje.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2afhquxmq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsytyvd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2axjroyev.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsmoefz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfyrjku.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgvpcco.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jzusvfvg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fsugyogi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wneshbsb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqteztzf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyhdumy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2huprljvz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlebjxr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbzyazd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipurfcne.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euahftta.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbklpzl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2eeconkqo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uucpoazs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wubfnypj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qritwssl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gskofpiu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqpucqi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlxtacg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yebpbmee.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sneoalxt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yurrfcjh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2patwghgy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbwnll.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xujuruey.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxjsvje.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oangzlak.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrdgcei.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpekmryx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rypoiwpx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyaegiy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejitgxqe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkxhjcu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2duzsvqyu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lynvukyc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2myaiisup.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyimhfed.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkajxaz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqbkcig.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrkexmx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwctuht.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pflnhfrn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2digncjso.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hguyobeq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2valpmiyo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwhuaaz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjoyqt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrjgmqq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bstkwlsr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qkouoone.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mohcijcd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhrwnwc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oduzsyem.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvpajna.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzonoxuj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kheqxsre.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yutfdeym.html


<!-- 参考信息 -->