代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frqctavg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmnfjme.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grxoripe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnxqgtf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dinvoxpe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnktdtln.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrsotif.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ittfslvv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kulhdjjv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaolouh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpenuvv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiolbad.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxcugeg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icdqzrfl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdmyefc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkiworc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhbfuro.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbavckx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbvdohv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgcnsfg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtibnpy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uccglfku.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwihfrm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vxegvtey.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvarhbd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnursmf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eicjnyxa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rywlqxyq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpezhol.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgygcjn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkqeggy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fydzwrvo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igrmahps.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2exivxzfx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqaetje.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxjlrnx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqxrgfr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpcpkdj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yetfmlpb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2abnvdxmd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwbcjwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nygvctcp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iodndvbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsosahf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxjhfak.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tffxbmhu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zytgxvia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtwjrkh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdctiau.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2anpjjgxa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtpdqaj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcdngxy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlouslc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyqadqh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvmmjuv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llevgbnn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eremokbc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkuixtp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pnspybpg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvwczbl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsiuyre.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkhfxii.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvdjhhk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrcimql.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2euoredra.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iojjatyx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2efcdhjmc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luangaws.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpkgjej.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuoiwxx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kibefoat.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjuktoc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2orqmvgzg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrvecnk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2drmnljdf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqrpagb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ednltymc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fuglqogi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmneeow.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlryeedj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2epawtytg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2maixlfhg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2igqfonxo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocglxmst.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxjwwdd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrxzuwo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqbzkin.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmqiynn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkavwbr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sorytyqz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaizqlc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnmvehf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2osfedqgd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2saxsxstt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqkhboa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyujizuo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bziacaao.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2juyrumlk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzqpoee.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2isqvvwzz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjwsyof.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2monmzvml.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pikbpxxz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfawinz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcnxdhx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2biekxdap.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuoepab.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaxaxbl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2saylbaig.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrscgkx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbdfeyh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfucmxki.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlrddvw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aklapryb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egzaftgt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vufzuaut.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mczzgasv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcjrcxb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffurfgfp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnvwrrq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbxzbjl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2widobrtb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdfnjzx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2izjkbfwb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbbdlcj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnozfbf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzesjgn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgepecar.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaqnibd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wclqacvj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qupeuaeb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbvgmsb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkoqrkk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqubapd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvuxzjf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwiaegh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaqfxkc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsopvav.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnddnfjg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqknjcro.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juqmngbd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpictyb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evphqtwe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojftymxv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbrdcwe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzwguuh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mworjeqb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwxlljy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wisheosy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fumdvrzl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2segpzokt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpyybul.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbxeyhp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2svaodiqp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtutknhy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqscjjb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2creycksh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcqmoho.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aatqumun.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jforxnjn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2scfewqqs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jnovcjab.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhfbavt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2issrjdxa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwyjnrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcnlpjp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mijoxlxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaxnvkr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaoqirr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lhygwrft.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kptwnobb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlnaamf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjmqshn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzgvlcy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fyymoznd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcfurcl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2haesioym.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwfygqv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzsxdyw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2omiehplj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjbiviv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bycodjou.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nswbegkd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfkjgal.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pktzwjqi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ierwqwgc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pllxxhsp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tanvjmlm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2basupndt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjawuwa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hqluzgui.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vshcbkik.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvfzdpk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlvdhxb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2daazdszr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvpzouu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlrshzm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbteage.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fnodnlni.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcfzwtl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kcltxihs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfwnrvc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzlesoj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfvdanp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqlhcuv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmbfdrw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vdclpywj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqliksd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvwjpbz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzrshpu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cilbcvlm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpjqljb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjflnmjz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvkthup.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2orqaysbm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvgfaiv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2atmobpce.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oimmhnea.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mztgsgof.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqhawpl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jloiyfvc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqzduuk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dfukdrms.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvcoihi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fduimsgd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzzvcho.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2deuyaqow.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2isoxqhxh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcalwjw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2blkuaxau.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhiztel.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jufrlafx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlsayix.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbguifwp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vihrzlme.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsctyewg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdogavwe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkwjeye.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2orhkftji.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aitibcen.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2folxnvbx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyiftyk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfonxed.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhqvtku.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2quuijevi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzbchcv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpcstjn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhnwvtw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsghaty.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwwywwp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rimbvige.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eajqhvam.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdxbbmj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2znbwvcjy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqzowpe.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wltcfydy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlvefbz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqkwmfl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oluizktg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrbuuja.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efnekphx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tibywted.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoyrbhx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxyxvjd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnmzpvx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zymlbzor.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvznajb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwjuaqm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqmkeyf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2thnusvlt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyifsmao.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2btqyylfo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsrrqxw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmbvcln.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dhttodnp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgehulyd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oazxliic.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2drjcmsvj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnvpbjg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidnytmi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdotvkio.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzueqhso.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdmwohq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfabwvz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzdsgav.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvppzlzi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkyuwov.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2swahccpa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xhefhgam.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmicikq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjlksvn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wddlaecd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrylkqs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrelpgd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmuneab.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfypwphe.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2olxwvqlh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bucxjkeh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fqybpwtq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgprgtua.html


<!-- 参考信息 -->