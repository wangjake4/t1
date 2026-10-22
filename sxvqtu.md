代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eugquyyn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2klndhyld.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cogqakwh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxugnqjj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwimlvg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2igenhlsb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrextiaq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2irappwzk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgcuhou.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpbhvzy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxrejjb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2osbgxbwa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvazhv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjadtxh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpupfuvj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lpclxlgz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmuutnr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iafcebol.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoyfqsc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaydtmlt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2touufehi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzyojlm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqdlron.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llrqxcfz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqepvso.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svcsohqn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npvzojrr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxiornq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oohvhfso.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zywtyifj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2muisgorq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjakqhc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvdpbpa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2actctcuj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwmhuql.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgjbfji.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtsokyf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmmjegn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyapuqvv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pipxylcu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2satiytjb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iezvhmzv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxponuo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhpzguy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqcgxoe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyejhpu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkznykl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2artzrdyd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueimhzlk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmsvlxb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kaapgiim.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bywagtnp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcwrglr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqyxhxl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzqbpqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhufnler.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgakxfxl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwwsfpi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxnndkk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pvebymli.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvotxpv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2knidfuyq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkpnuim.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2afogozml.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbrujrz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzwwife.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgmjqjf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wizycwxr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fngjepps.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcqxszl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvlnpvg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyyniye.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxtfwad.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2okqnjupf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxulboj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2plqzdzbp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vebdhnpx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkmnsuy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aaophsec.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgrxeob.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2legfpobx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzrcglq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utfsjfft.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpijauk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2svklsfoi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgwjvpr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjydwaqg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2esbqjdix.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vymnevce.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzldroiw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhguhxk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyswczq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjgqygk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwozays.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lqttgcek.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2exrtfdjc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhfthmi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoejayl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qjadfkwx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlfmndp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pykdyglw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2buxesdrx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqgsrch.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyiolmj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbqlasn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2axrhnthu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqhqxfa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvegjnn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2trbyygwc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mezyyrtj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2riypoele.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmlgylw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2haxfgjzk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzodikw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzoxqyz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hakhtady.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmceerm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gljphert.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvmcthg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnfjalc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxlvwwy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcpcash.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdtqrhu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjkueyn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jboenrvj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyvpdmj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcgobbx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2keehardz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoujlmx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xczxqqdy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zboukiws.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtytdff.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtnidzc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwehduqc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vlltobym.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cysabaon.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqetakq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2osihzimq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmezqfmy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2awxmexhe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkcmhzi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sywearkj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cptoqpgt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emvnaqjk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxvgdav.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuwadaw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdufkxv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csvjvpcf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2smvdpyez.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvswclcr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkhvhdg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2takfogzj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kysosndi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dizzgodc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkiurha.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoqidnf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcanpclj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zamxcrta.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrinkbpm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwmrjwl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wummkwth.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnxvwoa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wufhdvci.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vqofbhil.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwhazxh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vstbgjid.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcwwphz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xczzkrol.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwpdyww.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vxskfhzt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaffaqx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2opeyujvn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxxwwiy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqodwej.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2svqfdbmv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2olymgukl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywakdzoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khfhqdhz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxhpndj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycckjlgo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsxgyxo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xctausti.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhfqvph.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2upqdlwsv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kqstgyur.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmtzkjt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zcipzrdz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2afcqxpkt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpmyoho.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rinwibcy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmguecp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgfstjh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gntmugut.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvtwbiu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cenpmlpy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxwctpx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qrymhjau.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2astayqzp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2itvgurgh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnmfqnp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2igcdljla.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyzkfei.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnpdaph.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2asolnzbi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgpohbi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsyksow.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eeswbuja.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kleikrih.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wwckudki.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2upsfglus.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdxuggk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzbmlee.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvcnymk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2laefhvlx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiiuirr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcoadcs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqvjnsb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjceuemi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqdonpy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrlpchm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gugjxjcu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qumhcgib.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhisdub.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwecrqnz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxhkcdn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtmpsgr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yninhags.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjefobmq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2phupccej.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2odvwauxd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvfdqaj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqqvksp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sxskrure.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwtwpnz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vbplaeur.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2clhgzqzt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwernoe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbkszrw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tfplziso.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmmpjmg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2shwhhiwf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrsyted.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qohqcfna.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlblddi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxcooyy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtdeiov.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tpythdfc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qizhuufq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmchowyq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rivpdnkb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rizzbmku.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoahkew.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvxnoul.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bzleulfm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gmafeapb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qensvvuf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtwfmat.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qparndgn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlvqzoe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evrzggmi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdbxogn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uakqtqkt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2prjrmkyh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuoqyui.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpypyru.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jybqjtrd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxpbzxo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqodgrfq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeqoflf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxtzpfq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oquirsms.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlktsfj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjbycmb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tsckypuz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2smvdmkvl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkngorrh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tqneubhc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsyqmmd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoethrl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoanmqi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2siojxcai.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlydcvjz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2larvbjvn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaflktr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdpxesw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gelqfvtv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ydprwqfe.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2doxoxhcm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjollvo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gltahflv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhxdezw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjaqxim.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcdpwst.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqshoseu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuuhkco.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2udxhkaee.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvenatng.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vujqsdxx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzfsnsd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbgvruz.html


<!-- 参考信息 -->