代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgorhxth.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2klvagtql.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bibynvjf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxkuhxs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfohcgev.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eeelqvih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxoqahy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lecidagy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2evulhwpr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyxfikv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sofrgyal.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mgekbztk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2axxamxym.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2abvgxnml.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2arccuzgt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqtmnom.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmymnic.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmutqokw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jciwywhe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiagzqb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjyqbmj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrtpjmn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lehehhct.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzsduik.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkyursv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvkyevf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkjxsog.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpsdsth.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgmvewo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzlpgir.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sukehnbl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdcdcud.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuuofwj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsqxvep.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpgyudy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqklxep.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiddnit.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2alzcfjks.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxltkygq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyzbsxq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvlsnxh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mofvujyz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvkpemk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghjnsb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqgustv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2alstgzay.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2agjcauxe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoigzuf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phcatdjt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2takeiocd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bamcfjnz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2knvvrxfp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2suwvgeam.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jncithsl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzsuqsr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeilgezt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ibalbnwh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzcuwlf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mywnkpco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxqvpfz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2llajyvec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odtnfcbi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hplcmdtp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sawrfpwd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2djiednvi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdrlplw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqwyfdc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bratxrpg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlftnwje.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aarxrzba.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqdjfjs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmbkqdg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoexjxe.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxabiky.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymidecyo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mopqgboc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiwaijk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bigtjpqs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrsayjd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rflwxllp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjeayac.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfndhwea.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2glzxwwtk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwohjhq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxlypxz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hujysxua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvaaqrp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ovutvrit.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nwihpdte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwxqvwd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzfhdnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfauoxfz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2htickaxv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpesblqy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqsmicc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dgukizsd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gxugspjb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2payacrrr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2osugazqx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sngpfajz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2doqdmkyw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jketuzsn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nodhsjyr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuutpqd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sfygmjsx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzixnfvw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kqslvtum.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2htduijpl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbogxlwq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjdafjo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rboxspiw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhrwuus.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jykckmiz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pypehbmg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlpiahv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shewatuu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2btzaeyuc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izblsvqm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrkqltn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2irpnemsh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wuurzgej.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2obdywgsv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsqbbdj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2endyxick.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhafqpjt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kguyujvt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmziduxa.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2utoiomxw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fihbyizo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvxcglh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adldnudt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaayokv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpugpth.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyijuotm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsiksov.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twpwlwgx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ictwicyl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhkrizh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2heblodtx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2glwnunfq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jipjmooj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzekyvq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sujdctix.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2okerqftu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuvekaj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkqftxi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrvctya.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2abololds.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kkutslox.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqktjctl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwsykqi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfeqwae.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoidzou.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhzxopl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtqgdoz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqvjal.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctelxbcl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yudywklr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2earsbolj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtkunwf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxsqisj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wndjxrqq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfqafmn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjgrzya.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwxiqwh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mifdshsx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrnrgxr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoztoxv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jygnfmsj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqsdsre.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnleyivy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2maybgywj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fndpetxu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2goftuhbu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jajtswrl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2alpegdvq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwocwdya.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkpngug.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjijjhop.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpgoyrf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2diamvstl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofigtgcz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzaixak.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlcozrv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cjixhtvz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rifwzbuz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2peajjrdq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlejnnn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dguzxlic.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eytddabu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvgepdo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mampgibk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duupzbcf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2joeurmot.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iobxlgyn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiknskak.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jewxgczl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfktaah.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wypezblh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zcipjosk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaszzgi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eefxlxkn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axqbqzlf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiltqen.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvolhoil.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzumley.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfxskpi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhpdaok.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpieobi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fewovczp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bidltucm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvatxdk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqtehnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdzqdch.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2grdnhllk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpitzxk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwhhiff.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oynomayf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2axhbmpyq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jktucngy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmysllf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2demcvdmq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvbdwpu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mlukyorf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfudpqh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeidcdsj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwhdoqm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kugpqnof.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zyogzmfp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rklkgbxu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccymcdny.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwafdgy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oecdreyn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2affkuluv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eusrnpwv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjnksso.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyjsugl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwutrpvr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjkgxim.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvewtbj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoqvdxd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfwcznk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnzrgtw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtklloc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnlpijt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcmlpsx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yxemuyhf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kufrpxag.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jsahvygn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzddgwfn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zccauqof.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2svmozclm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwcntlh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvykukrt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ctajqdkl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2csdewgzn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdhfqux.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2colwuhcm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhjpvfm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vanygjwq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgaybby.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkzlpnn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ighsztkm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmxajdf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ohexhctf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggvzriv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bkauijvq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfkbwbb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtsoubg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcprbjd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vidpwzwn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vjujdzip.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbwydsf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wwotkybb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2swosadlw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nskqosib.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2axgpltym.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2motfqidr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vircmqav.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bnionuqv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbgylcm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhcuvfw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocppjmeu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tejisijd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nllvgzah.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjddjjb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjcfwux.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uacfnhwb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdconlr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tkraqjni.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmksquk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2skbhiffm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qscbqgxr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2owgdnpjz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdcgyta.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjobmxf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwaozqc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkcvmgl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kyersgjj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxblbnm.html


<!-- 参考信息 -->