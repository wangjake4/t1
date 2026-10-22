代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvasjag.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2loifpaiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sypmquju.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hedaaykk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhyyyqo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcwejpr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaunypg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yodlzqqk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjosnri.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjjqyjg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2voawenaj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uprfufev.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kydqxhym.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2urhwsrof.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmvgnmz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nziqmwvg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2arfjuwku.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrcrsfq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzhqcnb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2owsdlhua.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbwzxxm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nkotmyef.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2aoegepsf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxiinqe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sutczntd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fppocrdr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmhrgsp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtmupsb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lafnzjyv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnkmlzj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxovcea.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aygdsfpf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmbmdzo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2prrmrcqv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2itiyzbxv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwftnvsn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgrgcbj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewagtfyw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdusbfi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkkndmi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2einvnnbd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xjocnlde.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iuslqqsj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scadlexz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwmeukv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qskrptow.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwnoxsx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdxusax.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqjkkcz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hahahsid.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fepuneso.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiorvcw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrowfui.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxmdniw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdosdor.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujpgch.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lhicvllw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgnllhx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqvfctc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxopyhc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcuefgx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enymmnre.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiqjrnk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hspyaygn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjqlrpd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2orqjghyr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlyrdee.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfkwptz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyetnon.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbomwjm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhprleib.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hgycrlhf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cavioqzs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrjjfzf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2elcgeqfg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lncbkpvr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxojzubh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjeheah.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamrlypg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuyomvb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cepkqrru.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qroggufp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2abzquuhx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbxcxqx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zvawcmes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkolbhl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2opkmcime.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdajaayc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcdnqly.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjqukcl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjyysea.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcpmztg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcamkyi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsvrdxp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mowhnhst.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgabmtb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrjxjxi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hupclodl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zktegvtm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thhoojzr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pddumrxm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyinsou.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgrrxiz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeadxum.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfscfmv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqaejgd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdibsrr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tillfruf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrmrzbk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkqunmr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2khdhmzrr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxvnuki.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cefdwvsj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tltsythv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbrneev.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vonjwmbu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2swlgkqbm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmjrbqu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtyfzmf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mihnnllt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kegumbgc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmlpkap.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2msyviath.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoofrev.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaxykdi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2doaftkqo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eyygxpck.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aocgrbaz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfadgob.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdmxpad.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2irhgorzr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tksbdqbs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wugrkgfz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdygxkck.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dnezlwiu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjynmlzc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ubycrcaz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhhqupo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fossbesq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iryynwld.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ryinahnk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdopfnhb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2soueedqd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfepcws.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpgnqda.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2azfsdloo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ywteptmq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsbyrqm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zequcymc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfimyzd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnsoday.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aitmwskv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpbiiuu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpevlwt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqddttfn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2grxpgmfd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uxipigxf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qgydtaaq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnicvir.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lytoudgo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jddrmssf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtmjygg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efosuzco.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lecfqiyi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmprvcq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyenpogd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kykodpik.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cholkoyc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnmhbgc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcmhkvl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuglycp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjahrbgt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzkgdww.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmvlptt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukttphmy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvfehuo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npmtxqdd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkority.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ghowupma.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auxewklf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfkgnzo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiezqrmm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djkqpvna.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzodapyb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvchqb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isqjrjsz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsprjwe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjufdtwv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvhgvme.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbxaok.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjfgvib.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vegjvbhn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2upgrjhth.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwvsfvc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2poddqtsx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mueteino.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqklkkc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqogiew.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaczhkhl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lduzphsh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijefkbfy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sugeifzu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvhwsqv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gikcbwrl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tqznrihs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2somyxzhl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpubijd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2svsayjkv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrybtdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfrzfst.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2giswaqap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okuhjekk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nscluilv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2otzvzvmh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2onjmtfim.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiojovx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpgjdsf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkbufqy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mekxeydq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2opyhiuul.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qshkjpfz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgmgyqo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcuzrrw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjwapmk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2orauzblf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2krfaioho.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbopqwmx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrodkgq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iofejhfb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfifkvbg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoxnsww.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlljcws.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfykyjvy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgynfpwb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcnvuqj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrwsocn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkbrxvq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryibovmf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2igtuulnk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tohxgaom.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2beoqdcho.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaoszpz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rvurpotv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2irqvsqkr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lpokdotl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwxpbgf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2urofnpdk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wheeveyj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhfnslv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwmeddu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rehanptl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfyetoi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2maaftfsy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jokfsohc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvudrfy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqyyrnb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqqewao.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nteceqss.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgagpbw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vocqtyld.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnfnrgd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tafnrykj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxegowr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeicjme.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsmcqrm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zizpuhex.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bffmpqtz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqkildk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2quizpnnj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvhgfvs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kukhtqvu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdvkyuk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmrbugi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2svjihfbm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yrysvhas.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aicextzk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfiyrnb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2sibxkuzq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhpdaji.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkbiagb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbjvwyl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2winimkim.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcsixkh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oskuskwi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhciqxv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cexeibey.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwzfryg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rzndqlhn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yrynxamw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfeuexn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2adaqylxl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrkkabp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2imccbgeu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kphvepus.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fixmawcq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfljgvb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2svqgdant.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rewggnvh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frwbwiqq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbtzwqq.html


<!-- 参考信息 -->