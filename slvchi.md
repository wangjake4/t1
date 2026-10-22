代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqhrjri.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rctnaylp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcklultv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvdksnk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2abotpjvz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbspktvt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbjihrx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lndulepv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yesjcyqu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpwmdwp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfinjant.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aknxnikv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zjetmalm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ndplwwnt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ghszbnxe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmhcrmk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zclagbjo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vifpgcwn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pooybrhg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iprbtfue.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2buhnxefa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2riyrgulf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrsvnln.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuojcoai.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tedldcsq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeencpp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2epdndppb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgnlkox.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjbyuoc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnhsnrr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zblighke.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2walyqaxk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2esjjxial.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gknrofkp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmskumk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgfldtd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtlmbib.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jivkftaj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvzjkbe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvmwif.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzopqnp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2enqpkzdo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoojcoi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irovgdyy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxoalii.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqettwm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2joshzhuw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsrxogh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiqfsaz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmzwcen.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqaojbo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xseywfkq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzybkswi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyssrxj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsgghjr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhkewgm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icjghgpb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2clvwntjq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuaccbx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zxixmekd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znyemvwx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2imifejgm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixymwtpk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcrhaqq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqnglmy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzivpnv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnwjqtr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsfoxow.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmhrvlo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtivamff.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnglgqdg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qubojqug.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqetnmh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkronfb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaeuzsd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wayeispa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjkeqti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsawfzo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecruwwqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcgitgo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlzpnmk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tklgaunx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isxauzyl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqwesxl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hwksbnfi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2blrjwqvm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgpziio.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lcozbjiv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqvcucd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqzghya.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvzvedq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnsjjur.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2spviokpo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfdbvmz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqpioby.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxshnxe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2veizsgpx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hawwsrlm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxprjlt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nukzrznk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjqtbmc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqbhzlp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hneqsctc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuftric.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrvrovh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lprwblwm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cgecdnar.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fptyseju.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiozoqi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfvfkqh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzkewfg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgdwblg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lomxubfs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xywsmjlw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gprijvdv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpzhbwa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2suqbrwbg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mznjjnur.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmvsfcb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkoiadt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qapxxjme.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbwnkbx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2baznvwnj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zwztqwuw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgupzblo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhnyeem.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gygtswit.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmhdbsu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxqokjt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2osjyqzbp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhvxyza.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhviun.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vytaihvs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvnsxum.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2twgxfbtv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlnocqv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpbjilc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvizfsrt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoymono.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgezxyov.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azgvyvgn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mclyesxq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yaavqumr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sltebctb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvinufoh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2urzvppjt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttocwdrq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaheumf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxflxft.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2baxmjxxt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osafqipi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaeguyf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzecrcn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kstykroo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaqlrpn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2csbqrabm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2amktamgi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdclcfdj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2owieoows.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bnklthqx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrajorx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2asbbsivc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2teergeja.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gebzytkx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjbgqgt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtqjwrh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2akihqjtf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnviiebz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tukkxdko.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqssknvo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xfatckfc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrglvxd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyhfkco.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbbwoiu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaipfei.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2caywemtf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhmloja.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rverxhpw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyerlgkm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsnhzxf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igssanko.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvyefei.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iblzqhcf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkljgqlx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jnehczfb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkwrbly.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmcipnd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bueofwgf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmmjigw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qxicfjvq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjouhbef.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2howwjgjb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxkmgvr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjpjoan.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2acqhgigf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsmqvyl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xovwhbuz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfydnsa.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uapqhntw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xhudtglv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qchhycug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbihauc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tokrrguv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdphdkls.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjmdban.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dnepsyqv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcrsqwx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjkrjpy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nenquvir.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtwuyiv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyftosq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rgogmnpf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gaksjloq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmiszmx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkikxmi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfqikaw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvettaw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjbtynj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2thxdzucc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqmuqyi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnicplo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwqzvmb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exxjntfk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnfhraf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgqkqdr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrjvsoe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tgspqtim.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvowextb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orwnckjs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cktxjahy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rimohwtw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuiqjug.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2amznlurr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ritouxyk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgmoxnq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2etgntfld.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxxcjfh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuntyuc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2leiggobl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sahwuuwy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vuogkwsq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrezpyn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjbpoae.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcptjti.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jhilxrlz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnnoklv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2eepnjsrx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kngwdvva.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjpbsou.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oztzsnur.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qufklxxu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2agenuvfw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjfxvua.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxbqaeb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nyokjhjg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdydnimt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lmabonnm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrddcav.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eucbtark.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2petkrlgu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzjkyvs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfotkdd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2evbzodxh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgntqbc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bafrkpjh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxolalc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqjvwvb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bodnnwqt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeoabdu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2utkdbpbe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbijzjl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2azmjoagn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqhxbub.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oajhuzei.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbcqfnf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2neepoeub.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmhfigk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2artmdxao.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lxenrfit.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhrccxj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcfdmfg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pllizkon.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lpygmjqs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvloosn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzskgcy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qepbyuog.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dihsdwtd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2syiiwpam.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzzckfo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmqyqbj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkamzkl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkmffzw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkzqufh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwboatkd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nogpmylu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcphmdt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkavodf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhglfuo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcsmwio.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvmqmjc.html


<!-- 参考信息 -->