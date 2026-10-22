代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2orphaqvc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhtggcv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lecwocsf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqommha.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyusipp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbijovc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wasepcxu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bytwjppp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnheokq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbvbfmy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpnhxxg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqlkgew.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxylwwzk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgymorq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgscoiph.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuazvkmn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kldqimxm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lciwpfwp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbixonul.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaucuixv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwwvcvr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzvtdws.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aylcdmpc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyrqacn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwbfxub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcapqcp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuriuve.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qagdpyxe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2womhjiun.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjmaczm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unhvuxpp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxbxnhz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycejxbbz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiekjht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2znvcprca.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fliwyovc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtsuadp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyctsvx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcxjfoh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkwboed.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjuhigj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjrdhdx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmwwdua.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2acnrmtyy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2weiakdck.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2thapribr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2knmsbonx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjgshom.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkeuzio.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvgfbpm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjhviub.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtkgrcp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpozoain.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzkldmh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtootjyg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ockfpijh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2umaqavhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcrlvxa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvmiykf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xszivhyx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeehqma.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqikqphh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nswqtuyw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mznkwuph.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjslnsn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rekinbdd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvjojqy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gzapcyja.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2adtkqssa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzmymyg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uzprspos.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aixtatzg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgalqxw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nydexdvx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vauqrsdp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnwfnmf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwecbwxz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrinumzt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwobymnb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvyavyr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rwynyzdm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfnbmme.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjngbif.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xczmnkyb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjjnpdv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qchqripq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2orfzgxzg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgnyexd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tnefgwln.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeneixfc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2csfdvffg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljclvqfw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtkhqwh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lywvideb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzfgioc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eacenkge.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wkarsrgt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwayghy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aajsafzf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tioijsdy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlvosto.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yftzqmiv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dtchilsj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amacqnjx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcdjhfn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdwdmaw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qfivuklz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdkgisx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhgjyhx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqksnqh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwgpmax.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtanlchr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfafmpb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsfmrbq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhmkoly.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuoeaxv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmcfahg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrsqchf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xnigyrsp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdrrgmg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsetgek.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssecetei.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzhnhce.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qepegcfu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2arwwnlnn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrgsjyc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqxtmuv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2omajfjjy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eibnfnkq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksodhtov.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcanzfta.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfzbseu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kntdulkw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwqhooq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zircarat.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tapgzeol.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2krcdfotu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2btbexxmx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yoehmcpu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhjjijp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yscrjqll.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uioqkptr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqlnbch.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zskwsooq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyhkqyy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oolrejoa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrhdgib.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imkdrdnd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aamjluex.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teiqddle.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqygeeb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dflzvpmd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfypquq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dntbzmsv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mowlndgd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtwqhsh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmdthpc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoajwho.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxuwciu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qggiycjs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyvkxod.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gadhxbmw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjsgtbc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agvkouxq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcpkqtb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsnwpky.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cujjmnpj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2msquqnnt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cudabmws.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2alyglmyv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2utrbgbct.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcztszb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltewyxil.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sahatmje.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznuutfe.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2htrhgnle.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmpmoah.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2euebmqqo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvkwpiz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfysour.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgdjeiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgicpyl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqgehcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlkazwa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxqfbao.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcydpom.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2icrqrwpc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogadwehp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nomvnfdi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hipfpczb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkskvwq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kwljngdd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwdypbg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2guguwtof.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wfocmaxc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2exmupads.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2curifbvx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ionmlnlw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uunxjite.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tobohgtk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdfrwlt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hllmqpzr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvqoina.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxljiuey.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ymocalvv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkswjml.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dhojsyfx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2baijpmqz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2micupkdd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnffsmp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2expzgdrh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcjcrit.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2udzlfrck.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzupiqs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfaxfzy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhlmftg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbwojip.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bycmnbui.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2spgcnxja.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxddeqpw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gqacmrsr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeddyiz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbjjocx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuglnyki.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoccste.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2crcyixlf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpwtvuh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jptzovnu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eddxwtxw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2obyexzzn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdihwvk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyplwjn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2npzvnspl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tovatkyo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbbeayl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsdnfmg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmpxafj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cskkdcmb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lilnogqi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bujcfwbo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zffbrigc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvpxthu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lusptalc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtumgry.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2buhanimk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdzskpu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpzxsmk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdudone.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2doychvpw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gedgwpig.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrkopka.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2izlkbuna.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvogeqci.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvaefry.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbgcqrr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eortzpog.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoxrxyb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfjlkfz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2juhooriy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2szsasnpi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ketvkxcd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyidqpx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzirpcg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emxixdsc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvrsdpg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgwhbqg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwhfdbi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxiubay.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrrkode.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2drxieyrb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmdzixz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2emgofmck.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsxxwca.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoyefoa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olmexfzd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vdndhntd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wryprlqc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bgznvpty.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwugugo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlupurgi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2amjognth.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nhucbxgo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nssvipwc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkxaatt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdnzewb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fflqmwkk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cekhsspe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwlnqox.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ikifpxwc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhztopnd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnvxnuf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeygypue.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjkoqxw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmdpydt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxupjcn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaqzpdv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vldtrefs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyqvaqq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xougishu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tagquwfq.html


<!-- 参考信息 -->