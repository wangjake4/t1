代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpefjis.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfajxsj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sexfzjln.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmlfakl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuokshif.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2goqrsobt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaxmqlb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbyvkkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uurbflph.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ehybxaix.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjrsajr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvhkvgg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nakdnsuw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tovxwajl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeltwmc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ietbelwu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeltcsk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmirxnv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpsyuvn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlbilqn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2shofbinr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzbgicq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2svppjqpf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2siyhairs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvzcefl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nghbmzgs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqewbcqy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xawpkzfq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrmjjnu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvdxfpm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mblvyosw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfduhrzk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvxssls.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovribcke.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyvndra.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2noryslyi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwyrkhm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppviwhdk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zchyugas.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcoppbr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vtccgbuj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nszsfuvb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gajakbhv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkvduuq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zsejtovg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2olzlclhm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2daibbuxp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfdvmep.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvntufzz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vspjcgir.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jxspwuvn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnltgob.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnszfjvz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdlbtab.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gioshhmk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2obfcpwrs.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wjazoahg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpudziu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqsgcj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxsdjcb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuwnduf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxysbz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uzevwbli.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzufkck.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aryynfto.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqugsih.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvvgsxo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrymfpjo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2npjqtepq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jipyyrbv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lidhezes.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvxrgsg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcsasgn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gibzywla.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjqflrp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbmoetq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyrcrrl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2amcdknrf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzygpqt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2purkfkff.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyudyyq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtbcqkg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsnxtxi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2diejghhi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyyfrko.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zeerjmwr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dilzgwaq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfvxkr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2shtwqbvu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lnarlrog.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrcuoks.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuhpnip.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbfnxqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fphcwjuz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nilzdqiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdeklcj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yizajhga.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyudrty.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmvcwls.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkhzfoz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvnwdtp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlhnobc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2roouwftv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yodohufw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dggashbg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgvonhx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkkcsbl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoggxbt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oepuncpc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lslpolfm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2puchatko.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpubhlah.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khamdahd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuakdyq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tywpjpnv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzcztvr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uniofpmv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2atojmdlt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2laftqlxl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umqyedoz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfphhpfs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxumhmc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmjbrmn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhawqai.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fowtxyxd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdtocqu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfdxits.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2skifyxwe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2siwimxuu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqrvsfu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2glmzhygl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgbpluh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbmksua.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbbtfwd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qarkhawc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxswwcfj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwsbvsg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuzggyy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zxianngq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiyocli.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvreqij.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlcjmhj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgxryfh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfryvh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcwevje.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2meocyhem.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ieulefbn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hruagghh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2etnkoecw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2isaqidpb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sohaoium.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2esxcoyfa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmxubvt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrrxkdx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2finpnxij.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhpnqvk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxazzoro.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqhdzhy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npbwcpir.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uczjaizd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2njiepydd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnlijqk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vndzlbkv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhslvnh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxwfwjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fktuuksv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoctxpaa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjevyiv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hayabbss.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2foidvzst.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtpckvz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ceswxutt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jsytyvdj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdztprhg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzrrucx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsckieu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fooqhkyn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzumnvjr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmxipoe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2notiiapr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2abwldjyc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2izbaihtg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkgvvle.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eivohheo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eymxjyls.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrgwkwc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gsggpimq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpgpgfc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvjthfa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slyuinhz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgltsef.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2egtbqift.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czojoyob.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohmwthg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsurovbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwliskg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urekayss.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhgfvxl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiqziti.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbaimsy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whytltnq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwqstvu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgcxkmb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fetbatmx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcscuel.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2slmnsosj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbozvaz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgcnbhm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2didlqkju.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bjidgpgs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtiyyuz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdfwhkp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxbkads.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfkpcvm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpuudsd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sravklgp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnfttgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwavrnyw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwwltar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umcpkpwe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uvemjrxu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxghfhk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvzjspz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqwuenn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2koqelupa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mynswcfr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsbsjka.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iebfjdsn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvurbhy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkksxik.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2isszsfma.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2odhzewgr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kviercpe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzyfomh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2shiamwoy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2drbycgnv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kckjukbv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jezxwqpb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eajfmyvb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vefnotoh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cofdipoa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfacwwm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kouqwsga.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgpmvft.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxetdxft.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2roqnvwff.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqwzjsz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaxluuz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjtnmyf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dppdjurz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yffyxcnb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2szgpuyua.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbawciq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjcxda.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pdatazll.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuynvdr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2alqycjfx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nztzsfhv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fivisizz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mioysarg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mioqvrat.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wklytndq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnhxahk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2akigypbz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gefyldsp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iabdsvdm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2norefpvm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuwyaqw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfivmzv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdhjegk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oixxxzys.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pniipwhm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zunnjfkj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwfgnpu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2umpuakvq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgxayuf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkwyltp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzwfcww.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbizxef.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiisorj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ntveibww.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyvcsla.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsvhibv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwwfbnj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpfdydd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmnnlsw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfqbjfj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wotyacgx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yybxnszo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpaxfxx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxrabqu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2abwzuzfk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2trpzmhqy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvlygep.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdacmcz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlnmhhg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuwiexe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdseslnz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rulhswvw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zneownqc.html


<!-- 参考信息 -->