代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdevwze.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2orvdkovx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvdpfja.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqcukes.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eingmxyl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkwaakw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaogatm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hphwrrwp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgdowyc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpcjmom.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxejkwrq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2etveqxpw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsqbhau.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gerdvgvp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqasfqho.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfavuiha.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbwxwln.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jomqgzim.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvjaqyw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gafxvnyc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2haetlpqs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qefmxvth.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtggqks.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpooilqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwijcjt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvagekd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdeagcn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jztmzlbp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkqnksa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhfvdyc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wluahyar.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiqlqty.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbghllrf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzliked.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfxfkxa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bczclikk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igwqczxb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dahreevi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zglgntwx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcqhmzk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtrzrus.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sgczbacf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvbgsqn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkmltfn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvtnssz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2atlrdqug.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2otyjlqqb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dahxfivd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhbxslt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfbdovy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzezwafd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtlehnq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2quwiqcqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjgtfxt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2womrlcqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yruaoewc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrptlvi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nijnsybv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phnsbjvk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2updzmmed.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oxswysxt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrlvudm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2epmoonef.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyaqliw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxvzbfj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhxdzex.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eudjcqhn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcmqkre.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nxokrvrn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtjhelm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcmpznd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkycxch.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjlxlky.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2haqvpnvu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlisabsb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dugdrjgf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdcwbmu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmfcgql.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kazulnxb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpcmmrk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ykplhwfd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcefdpa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxbuyty.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kprvxkbo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrtsgos.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2evpjzopv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dsndioox.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldachtfe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvxjxpx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2itwtntli.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2naqpwvae.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qweuaocf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iskxqgqd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xatiwsrt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2maenxjtf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2okihmuwq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fycfuwgb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfxjbsq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cankkqnc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mayofbje.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2llvmsdqo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqossqt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xhshjimi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfdicwp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pptsrqld.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2skitpcwj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoyrxdp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oesrkzeq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjifuok.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lidgywtx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wjraeonl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cortyzrp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2afjpvkql.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2blfrloge.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2doslfxgz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gswsyolg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnvbewv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbllkcjp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2baqgdrre.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuufxcz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfujpity.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zoovlwhq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkygwjh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhaxofj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2itayzfab.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgeqtpm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzmfbqx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfjspus.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiyhyag.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2efgqszud.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdytdx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2egmoebsq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxacpei.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmiqepp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2srjtznck.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sapwgivu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2susciabq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzhsvqn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mafbexax.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmowpzop.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsgmxno.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxodtsp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlmkkci.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwejyylq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaxwfdi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltepvvdt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkadwqe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsoyooy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjxvorm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gulbzusj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyhbory.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiujvsa.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbemaczs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qglxhqzp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anyannhh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxuzzcl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koojffvq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbbjwkl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnieonwg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2viahwcnq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvyavnm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wudsdlbq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpjegzs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2reyaabzc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lguzlnvn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfdwcrd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2komyorqq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2paldjamh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjlvyrk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcmmqlb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoctlcru.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcotodn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2caormnuv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jampxccx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhyswut.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgogczc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpulwdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blvilxhm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuczqpoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smjezppq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xokfnpvd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2inafekqv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fidpubjc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmloilpe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxtkynk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeyubja.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwvcgng.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbwtaek.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsdodes.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2laejktly.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mltfdidr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpfsrvi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2stpvttji.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdijlbz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgxbjwh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kihywwuf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnstaqa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdccqoa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2usxdgpvw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2myihtdjn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kaafnaho.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cntaeecw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvcdksv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2klpqygdx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiasuro.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aplsyjsa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqomxatm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsunnvjg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hqafobxh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkojbzcw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdrorwg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfwbtic.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxlxygr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqnmdzz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpllssk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pakohyzl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2goiqcrps.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjmpzry.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpcynni.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsugerz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2grjvmosf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkyycxs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2piggcpkw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2prqmowat.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiepmss.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gvijpmwr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jafnzjwb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmdmhce.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtyzzru.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqeuboa.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2azeuzlqj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjfiywg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cfinhkpo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkrykfo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsyivqr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2txapgcdr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2agupsebg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2evnbpiyb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2phyafzbc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmwgyap.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2znvtztnu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2upecpjyu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhbsgus.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ixogfjwa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wdomnewe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnotrqk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbtupjd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpckxbq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbqmqdt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2weiumdad.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrjhqzq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zypbmotr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2npdcdppi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vosheyov.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnshzpn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uykbeeew.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyxjcau.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqcbbev.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sptbbnhn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbopmltf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uldbwcmx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eshuyuax.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzpqvgt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2btxersqe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuzyhdk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2autsqmvl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkatxqra.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyejrfx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dapicdfk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkibwyis.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hosrfucd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpreztp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smhutwfq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjakzoc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ksflggww.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtiypsb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ianiphdi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzkzcls.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiyilvb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxtmrms.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bldqbsbc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbczcipf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkubocdw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmnvmgo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpfojbu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmzohlb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvvkhww.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qplcihij.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuxossg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gokowkvc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtddsdry.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeyqpbz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcbrufo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmjflak.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lywftsik.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2loqhntqx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sitmhort.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdaxjcc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlxckdj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvehsvq.html


<!-- 参考信息 -->