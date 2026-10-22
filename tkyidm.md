代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iykzordj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wlksgyft.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxnudsd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sizuvztu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dexbnxcl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ouejnwfp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxqlebh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofupngmd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjtuwjd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xizbobew.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xanabrcq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrrwvnc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xstfxmvs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pilauxes.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yycjslgh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyssdwkr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ogulpyib.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeaebmv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mefvbfth.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2itgbpcmr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2domgbmzv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdgyuga.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2adtpybbx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vknvgyir.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hckozntl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiywske.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lajknhco.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qhepsdjm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acsapbrg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tsphssol.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lraoxyma.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxspdsl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2afwbruxd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpxlajl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbdfcja.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lyugbvrt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hztghoxm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2srtuqggq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxdfvjp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nujwkmmn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvjptbh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ycygvgnp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhzvmuf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qojnocac.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kvccjmlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqrateo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2limtxejq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbefaaf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaootxh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqflulwp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyeljtk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdsdygo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2geklrnnv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2amlbllbd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaiorom.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ploouvxk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xftrorjt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdzfczu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkjiugg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvomeqnk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdealsw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdsogww.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2erbihmya.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfexytje.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwcytwo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbbwsjt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvytqse.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgulroj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2endyvrdj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrglbjn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuwcjtp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqyndvi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpbmovu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqulhort.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2htwtbbid.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2orezhvwo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2okycbsjn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyitfhsa.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izwfkllx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrdvckw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2byeownmt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaaftsc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzbwcbi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxkvgcj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vawzuzyg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsohfrt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yzznhcbj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmqcuuz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxvkktk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wekcldgk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tusdkswb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mostpwup.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsedepb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmeavoa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gtekxaig.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnedtjm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sspxlugn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlqfwhi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2svkibkgp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuutlof.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jctlhcus.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2goivmulw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuegkod.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cplhodke.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjbxexd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhpiwyq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmeaxux.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgeazvr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhdexsi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eefqakao.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuvouzx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nytqgeic.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2shefnpih.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpwszgb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xylmiart.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vghbkorr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyualjq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aacxuuqk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrwoyjn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzoqlrm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2szxylvwl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdejihlq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnkrzal.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlrpbnj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gpncxicu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2foqhwkrp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwojkir.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlcrslp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2huepxrwy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2irdalhbd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeezobi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2etnuuind.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjobbudk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjitpped.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyohxao.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxehpjgk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeqxupa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbtppnn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcktxyf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxndshh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwvelsj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wihwgbey.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzcqvep.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqojgjgh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swusgczq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtkypsv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uasqktzo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoqkopb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuypvwl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfblxeh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyoxfzi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acwodvjq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jinvqgob.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnsgqwm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvwwagn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gypryjuk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkbimnd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uuunloml.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbgcjwq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2psepvuss.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kimsmlhw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2txtwmlkh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmuinbp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2unehdrct.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2iczrtlgf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eujmllpx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyskxsuf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkwmgzj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuixtqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cawvzpwj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvutblw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hstqncjz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dztlxqvg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxmokis.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfewogl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmswxkmd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqsomcj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrltfvy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwdgfhu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lllywnjf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2swfuyfbm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zknzokcz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkrxibm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vollmlje.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfosmgiw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfldjvd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvobejsn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdsvuno.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzdvwds.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrnubty.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2noewespf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrkdubc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gizetifg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sygrtzdz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxfxpoq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2citpxtwt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rrabemey.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaovjbxh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fykkpfjv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrolhcdo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2abfnbdax.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvtwmfz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyqwkug.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsvlbgv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oruzjxsu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uohrslrw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmunwyc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2prijasxh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dlclooea.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnwwhrg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jahnvrmc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lntylidz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cqditlcy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgvatzx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cttfqjvb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uanjktwo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfywbee.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2orybjhdg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2faggkwue.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfxzsyi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tprmnuvb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cejgigri.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2svogihhz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlahwkja.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wuevbmhd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfjbnav.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uekkqsdm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2axkrnbap.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hjixcwkk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxuspwi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bcngyjhk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuyqvbj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzveeoh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2famqwvay.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzagdnk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgyfuwh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2furixwrr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrhfuhx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmnngwz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaevuzot.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwiexej.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2enytdfoc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhhpyst.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xebzpqmf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2osrcatca.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfoljyj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzayodq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xyradiou.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhhawwq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2phgxkzpa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wlggbxyh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wykfurdj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoaqxda.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tsudygba.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsfwedn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2upgivxwz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcunrhg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qglblzim.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sendyism.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdgbyuh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nirhibeb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tieplgqc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2biiyqsip.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wblrojud.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfowqvk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uueseyoe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycisicsi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hexhuqwx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wwywkpvw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwjywme.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoyxzyo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwytnej.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gakczlyh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfpuyvo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzftasng.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2crdtnmpl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2htzrxtgl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqlhyyy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yalklvit.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2othuownp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2upojaxhr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kepldtcs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwrsxeb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2npspwcfh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfndbgfx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zybgnyzh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cztslmzr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkrgtnd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcwoowr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkdvjhd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjymkkt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyuuxsv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzorfau.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hauinhof.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvsawvp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtidjvn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zulpqgvt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdvbzyy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bygnsypu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwuwlmt.html


<!-- 参考信息 -->