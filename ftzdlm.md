代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vunirbjm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2juazucgx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbsvnbb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcisdll.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxorjzc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzphffur.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2euzstqja.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlqnveu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2svxycfld.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2woryiefs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqawhbc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kzelinpw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqsejow.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2affqpona.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwojjor.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdvorcs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rribpmpd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blxwzvud.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqebpunp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwzwglv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cwngohzm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjfmszq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cymlnfhf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eugiswvz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kjobmreb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsdcdip.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzehjyk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjgubc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtiykrb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpnjeja.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2quywtyih.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlntgtns.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xgncmnij.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hahqousl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsdnbpn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejczvhql.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsdkwws.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkxxoeh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlaphky.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfzrrpn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aldpywop.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2melygrhl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuuvtrv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhditso.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfyfinf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnmndkh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpmxfcf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfzixmd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbapquh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsayxhgm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vftbirdz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvjrnwi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxwaggu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bunckjyu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxewhis.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmdduxi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzsgxda.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgkrimi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uekrxtrv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjacgfc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gemuwbto.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abqunrgq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgnlawj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mrltzees.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2citvniki.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vruuuedt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuzfocm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rqirwzvm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqkxfqm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfjadar.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdnudhp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdiauet.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2grssnygx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iopbxnat.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtkttrd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oiatrhdj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmcwhjz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrxwpws.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrabcrjy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hejbrfsw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybygcgdw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tblomtpj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdfimif.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kcebsfim.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2btneysxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwriqme.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeclkjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agplrvwk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlgpfgm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyejsolt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvboxkab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnzatsu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhrorzj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrckces.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbiyxir.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcwedoc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxjbqlv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkilnjn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jedgzzjj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuvfcrj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsanojb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2muupytjd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2apbyssgr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwhvakq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsktstyr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2emmpexny.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkwesor.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2icrrnrhx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoiqjke.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdbuznn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eorjhwea.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2biyxtche.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmowqjc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjgmojx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbavtcy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkphbhnk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnfoawc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlsksym.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wsollszf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrvkfuo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kccgrgzy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zswgzrct.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rayykkwf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2drbmlkqe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ljihxuvl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2avzzjkaa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeikevj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuluctm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ausgjnfd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zblbavrf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2huqnsiti.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2moshcisu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjohsnqe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgncbtv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnfirzj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzzmghu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dsljfern.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2szirczjt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eytjdqts.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2suobfkhw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeddswt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmjxkpm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kibmntdi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgxjmve.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjoqpfn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqipsvek.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnbjxed.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmbgqjk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hriddtii.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpuzxwf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pjicztqj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bysppesz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2txeixhjl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhqkiir.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtouvda.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wuetqevj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2getpmejs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaygace.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dilemyvt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2utftexiy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bulvwqxf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnvbjxu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhnefvg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2arrmlnlv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaelqch.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcnlbkd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsprzlk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgwrvd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrthkvv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kijknjfo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vschtetm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yywvpqqs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjebtoe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfecgcb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zreyeqho.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhmblzq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzautzpr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qttxlrmj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tzawfypq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jylleimj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sqprcjql.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kftegsqz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hufsxumh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnznjvi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2byajmgtg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hftysarg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjlfxhk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2amlzpwtm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzinisn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdlgmrz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtryywd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gisiepev.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwuzyiu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvrxbep.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeutszge.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xhshlutv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vykvqqxj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fwouqmbv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhdsemq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tofttuoe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpyqhwg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2esrrhdmg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2paudijql.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pnomrejv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkhzltt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2redneedk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2udelkdls.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vdowsyws.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbegjylo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuimrdi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpulshz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edsqxtci.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ptojahvd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2eidkilfq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2taiufvpm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isqkqnzn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2aihtixea.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcdaaig.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uoupjttt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2acynxyix.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwglqpay.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdrgnwz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qbutratv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzbnlkg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cickipba.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwiixah.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqnwhnh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nspqsrdl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzwcgwz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvgtwpo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uyihoxni.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaytaqe.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2izymupfm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwgfzpi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmvlkod.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkajwqo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmknsuaj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqdtpym.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aahvmkab.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxepjgm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaelixb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgilqyq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmpjedh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhykmecx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kylzlycm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2czyfmqxt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2blgsjobg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkgwgnk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcqtnet.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sazbniuv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrihiii.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmdxgxu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlseuuz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kszybgiu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxzqzyk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaakexzz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szzqxqhj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2grxdnghg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2izeokedp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwreqdb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnlqvxn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegjjfrc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nalapfad.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlhdpsz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsgsueu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2soeghypc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2syqxiook.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzdjeam.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmxcjhb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uugnlnma.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2elvtyfvv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2haziohio.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvcwrey.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpngoxx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odenbnxv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlghdab.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfevnka.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2glofsylm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2whcmovru.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogiwtqj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoayphc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpgzygu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwstzdqj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wocrcfkq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nentxlqr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2prpuedjv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuvkzhv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sliitrix.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyltahr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rulkmxuq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uypfkodh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgbqxro.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uaevctmy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2urjmnsto.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfqpptn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2usyfqcnr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vloypvdb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tohlpqcp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnkhsme.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsrsofz.html


<!-- 参考信息 -->