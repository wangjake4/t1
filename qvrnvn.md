代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuvrejk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwjbtst.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fppzwbja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coleacdr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2keulikvc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuuvrva.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lrodvcvl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjprsdp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qtltclaz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfukkzl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzggqjb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfehfzb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkcfwoo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2smgcvwul.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrningid.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxawlbee.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sspmplir.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ielpxufn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yemqqvcl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqynklza.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnzuupt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqvjhui.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zanflknr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgezdxrd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrsmhyo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaviutm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2prnscfqb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biubcotv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjlswmk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgbkdnm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aymnxlxx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdkjqcx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnqrufu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vylxuvmi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2blzefkpp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nlleebba.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxdqkin.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuabohmm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2clmdayid.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2eamcifnm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsloriv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaijdtp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqhkugk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmddeud.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwypmcm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxddehv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpfowpm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlutwwk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvxjaup.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2evojvqtr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcgrwvn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wiitgxjp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaqyrfp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcchhil.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2arfuadct.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pggzwyxt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pzutshfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrhektq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hldunczr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbswocug.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2daxhqfcv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wluqghsv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhkjurf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmfnecs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qblkmkdj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eokyyckm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmgspfr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsklzwz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2davvwsow.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhpfznb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2otvnqvuv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmjmeyu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2claxqvwv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xigjnzxh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2npxvmijo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2upkdlbqz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjsjhfr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgbrolw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrjgnkj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgpqftg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvjgotx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfklthlq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcakzhh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoezafu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfnfiaj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnbpoyl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgfngwz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fshhaxov.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xnytiuyl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2adqkevwo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wvurrcgs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjguukeg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2daczvuqi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqxpqnp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcojzrdw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzxpwxc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxjdxrx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiykarm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2diiznoqo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssseggob.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyatarb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pklugtwt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vircfemk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2luvxecsw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sixypmln.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kesegibh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nscemjrv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ninusewy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pvahoupf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lknrlukh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmfrewf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgoewnj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhlkacj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jouymgim.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjjsdzg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lofemttx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsqqplg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fourandq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ibunrxvk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckryayqe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoqsxjs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2conceapu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgycavy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sbamntoj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqwpfgg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgkkspt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiborzm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2htosmvgy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbudhgta.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiimspp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqoiyxh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgllrtoq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjcymud.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2atnzgcve.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpfdgnv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yuncwpuv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpyjwgq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvakykh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvevttjk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhsxywa.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgjrypt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvqalwm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stwwjkww.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxrympz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wynpwqur.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2epicqyco.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bneygdqb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfokavmq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyogyqb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deskebzu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mftftyis.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvexokmu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hzihhobr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhtzbwr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwnizjs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxjtagx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqmhghs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrvdbre.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muqayiom.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtuwsdl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urciuwvd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxgveww.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcpdtbe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rotltdxk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxcsyzt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlasbqv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzvjixo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxeqtfu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2faltcgjs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqpvihw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2spqqfume.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmeibkx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrjnqqo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfzmxgi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeghjxc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsyzmco.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyssuqnh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeqmxzi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgneyxm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkuvhay.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqckdkwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwymctlr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxatgffm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixullrmg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwbohvh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjvssle.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2enlkhpyl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgobwvec.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpzisia.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhftwhrl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjuakso.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gvukanha.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfmgul.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmldbuq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdbpcpl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yubjcoja.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfmjnjv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pudhmhbx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbnaalm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ownthxla.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2adfcposu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzipitd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zipglgye.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vquxdqps.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mamqqvzg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkaiccr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kuczwykh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qreikbiu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifufympc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxyuysx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2swvwvumr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2stjtridd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmuqwlp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfgimla.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhbsmgu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvmsici.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lalupfty.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2khhardjb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2grpwprkl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmgauig.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eromwnhb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpbiiss.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2waloazum.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqgvtyw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpptnfd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgbibcr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvgeexv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2enimgrjp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzliyyeo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kkflrbjl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdujrdb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmnfyrg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsdfvzn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaizalt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pguizzog.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzjllyr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpjhuyo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsmyamc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pojkcoef.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvmncvz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpfzrla.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqilxwp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjnabmz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqjmvvu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lllkkjnm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqszjkc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkyfylx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2axcvkknh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdygyuu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzcwlaz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaprbwy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnpmwzj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeghnat.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sajbrevl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzfofkh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2udvnwpzv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kdytsayf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dehyitom.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnauchs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmsvcon.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtxyrmg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cllrjgtd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gydqflhh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twwisdyc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ubamldgr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfrbevt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wvccjsyz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrtrdqw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2blifsjso.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2skdgrdoo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mciyrnpv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyomclh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuyfxby.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jekzguov.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tyznexdp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnsndcr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrqgmyv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtxymsz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bcinpiwd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keyxqdxf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qgofnrgf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qhahxuuf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2joaldquc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrctzdsg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvckpsj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxykgul.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiikhfvw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpqahht.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhxcbld.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2twmdxqno.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2juimkrfd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2duggkmcv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qytjhlfd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvbfvjk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbozpob.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isedztvs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbfnzrz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aymixico.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqjsjav.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imjzdljx.html


<!-- 参考信息 -->