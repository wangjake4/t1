代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ditutnam.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tazaypgn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2axlylbmp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnuycua.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekonbuwt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2byihcxad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzxtejl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmudbvn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2voyefmhh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnokoxs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwkrqzn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjedqet.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrrulhu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpocqfa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgvsdvc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xecujmdl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaokxyx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdlbedd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkishfj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zimlnpiq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnwukej.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2llcstykt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfzrfge.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrqgzcm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kykzbjtw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgkpywy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2usuiwrmm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mocximge.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zvywgodi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zufzakaj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpgobey.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaeoudw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2btmzijcp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgplbabc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smncisaj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2maluyixl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuqgoaj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fipvrupo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkcotiw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzlxyok.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfipmpr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwvhfgn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eotwcvhz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xposmume.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mweaasll.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaceiis.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sbshkgdd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrpnrsp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzpmqok.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkhktef.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mvctrhmj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagigsc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oicyuwvg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrvzwyg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gakuyeqz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhnzvwe.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dydnooeu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuqcmem.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpueeub.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jutakuef.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eobswyhj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgugtdv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2addjfhyh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghltcbju.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qaquuqby.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzjbccm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rocldtbb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdmxdmk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnwvatl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mreblvkg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqznwwmz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2obsofgfe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfilzaai.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdsnyci.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjryhmj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvukmwh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aabprscg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2njxankop.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnqlugb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2banswjmc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqcmbey.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qpthcnsj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuapwht.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnjowkz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quqlsyix.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfjjstb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyijouxc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlgkejq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mckpyxkk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjobidi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dunlzcja.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfjhlho.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxmhojc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2woluqgfc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruazvqvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ighakldg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dckyaxxe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hctbrauc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzzusao.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bipgxzdw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ojffpwyp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhksdsdv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwofdwl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxziaep.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnpakyq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlmsgsp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2plshnpht.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2crkjlpld.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoumbvr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hotqfbyu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uikaenxa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpyrxsy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwrxgty.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbhhqwp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtduqxmg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnkegug.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bepwerpm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzrowxx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kucdqdqq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuahyqqz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2caipteeu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkgkadz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tlumrouf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvsvftk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjnjufn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kybblxuz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrojbpj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oddlwqlv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpchxrry.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cziuaikn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuongpc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvkjufl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2klzeqvyx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tngkcasp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiwckbn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmvhaul.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbziypuf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgoyzfd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2baqphlfu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsmgmph.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2detvclsj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sygartse.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxkezlu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sapqdrte.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2irxycutq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpikrlda.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2npcqjqyr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmxrpat.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvvanxb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wknpayrz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2msclxank.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2icmslijv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wsruulnd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2utkdhbpx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pvopjmvk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnncmpve.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkkabbc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tloubjue.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyyeisd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyyrvyn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbyeylr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwurpey.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyvryxf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iinadxsu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjcsikh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgslfsr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjpwygs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsufiwsb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiwzomt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxiksog.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhajgpw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bonvflgl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlngsgp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2amiqhcge.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxxrsrl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaejbsh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgubnwa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eccbjwlk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jowlzvaj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkrfrjj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bczfqesx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rulibocr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrsscyi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhokskqb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlavfbb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwbasso.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgmqfrj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgporaan.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hqclnjfc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhqtirp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcmqqqm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoyjruj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyguknf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eetsmfgz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brqefqox.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgxozon.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeboedmi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiubvdh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2udpwmeof.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzsambw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dstzgvkx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzrujcp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hutiefwt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2spiodbgr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvgyhox.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bsobdeoo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmutlvuf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kloupukm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewugjvr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsmkhvg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsvkkmt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzmvdsj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwxqugi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2btfbynvo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbswyqhn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ifabxiak.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeekiux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zefahhgk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiwshel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atavprjk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbrsgtg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2brncvefd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxrxefk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhtydbj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zctjkxqn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrldxstq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqtnhvg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bonevpog.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhwdvkt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtsfbhp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdfrjir.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaqzlyo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2akrajjlx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vynipwpj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiyaaxv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrigmiz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ovozyvcq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebimwbt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2swghepmo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjoxmob.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2swwtdhgo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvodtdh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgltwgqn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tucjvzgy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiohntw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdvhdgs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuenbpx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxigjlu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnoslpm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhhixay.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kjazwoei.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fziefwaj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhmiyrp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfclagm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwlgjrg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2smlhyesb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbomrvs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nktfngui.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmcbhuu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihuahzv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fmncfcpy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvtpayp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgortvs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqzmuco.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzmyxva.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoeroir.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tppgxois.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uezgatzt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnxdwpf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqptljeq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtoicug.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvpufbg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkyipfr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhtkehn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdnxsfo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tkomzftb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfzeqvk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sypisrqk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzzkdyg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vghzltve.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvzomoj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdxogrc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkqkwib.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ovynfshs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgtsoxy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxpzrpu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuybwkg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2trzqmyww.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmpgtko.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjtorhr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2veshihsq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammvjtxc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2soxyqxnd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgypwtb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2buxpflyh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hobornyu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nkulqjlo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qonmnnbb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2otjyecoe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mufqtchy.html


<!-- 参考信息 -->