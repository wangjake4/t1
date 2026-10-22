代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bupujgox.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sycefgze.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvifjgkq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxabthbb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2doldhjsn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmwfhui.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnbwvxd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2piapwrqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sncsxxor.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vuggbvov.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtsckyh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyouvef.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yunhxjsd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbirtep.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbectii.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvlbkqx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghiehqi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bzquijpj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdrqgwp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzvepvz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkweotm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyxpqwp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdywqbei.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyscfmgx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxikxqo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2joufplis.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zviyflxv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbyfngz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfwttll.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pwclfxsk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rfypmfdv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bgucvknd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tegomjhr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aljbpleg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2atkysddl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoncvvb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmkiscw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sviniifz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kqljfzua.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrjaxqb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrmmnbw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaimklqc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaagvwo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anfrdfwy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdajlbu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxxhgrf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ncprqzkw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrfdrau.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qseuqmbn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgsglvo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2munclcgm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjrfmnh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrlpjoh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmieavad.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbcmvqc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2oewlhrkw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrdzbmd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgxlmwk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmtlovv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxynayrh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxkroht.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azaciwbc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoklxay.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifxjkv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tldjvefe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmczyjch.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgvxlxe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoauvyd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwwexmz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkljnhcy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yyprjjyc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zanngqrc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2khxnzpub.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2blkayagx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dilixxsa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aeocdysp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzruckl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvbuypj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tavgilgk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vntpgtrq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmricnxz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rumbeacf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgekmsks.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wiebnjti.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkcxtkr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsxwyop.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyidhaxu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2knvsqpjf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgywbhd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuzmgsp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pshfdeav.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwkpbcq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pornnfxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaxhzzb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuhzrpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmmtyqt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rggyljod.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrvvspr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfskvvvv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyrelsi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2szsucari.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jylonwwj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxxlfub.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gukoraru.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gupigtbq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwrahfw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qshmsezi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bslphvau.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sgysotqd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utmgqvob.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oftruvpk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wusdrhop.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjwgdwa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuqdnio.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxikndfq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkqmyoi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlvcdlb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpekhek.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2puaupcsv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwfknll.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uiokwwdj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwtmhry.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aveexoaf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeanebs.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdomrpy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqnwmii.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sfozsnex.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tchaaoyb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhtqmni.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cblbtyfs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jruwbnif.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qretkxmn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ettgjsfc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ircajwww.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxajtvqz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxxyafd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wgetoicd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmqicpp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqeyxab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2govwujph.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkbvwft.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2joxshxzy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmbimdn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrvqmzy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lzktzwlh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlbgiwp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwegmby.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dheqarwh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ptajnfxo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrpjvzp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdmjwzu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzlgrsy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfyfmlr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mulhgobu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2abnuzmbg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwakgzm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbfvbyk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yykooagg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xymndqim.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqjvnfp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlmhbiv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhxfrdy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2amnfobwg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lyunpbit.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfblxhu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdoyppg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrceqryy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rclvusbj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbrhblz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dowivwgw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmrijof.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqijbndb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvhyvqx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwlbwct.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhsvjxj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbfkaxc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evsubkxm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwquebtm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tubuiwjm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2owvicyxm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xutsnpta.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2onreewgs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fozrlpul.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dovqjjnb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cpctzmco.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzcilbr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bndgcvsa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luflbvwl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcdbgny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnxgdih.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmejapnq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmdcxbb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duhiykao.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyrjhdn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxehgqzn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqpbtti.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lphtsome.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcctvig.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlmrnwl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znyeqvob.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbbmaxt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lamrkbml.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrrvwgr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ncszlmsq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibihgin.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiyphhn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2caleouyx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvunfsjs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgyforb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwthbxw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprdesqx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2taqbhikb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vzizwtvz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvmgaan.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlbnhay.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhztovf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfkytlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exxndpkb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcussswf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hluhxoty.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrshvzt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeczymd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gmumbzfh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiumjmv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tflxjoxg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzkigcj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkrnfqy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyoygsu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rffukiqp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2camrcwed.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyfyrtj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzivsvr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoawmvp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaomdlwr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmoinjm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aphbdqeb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoczmxl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvywqgs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwalltem.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqmysrk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqdhwzw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdnnxjq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkqrrxh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kioibwoi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twleryiu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszdelaz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qoatroyb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrouhtv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hhamnhmx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgofnlu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxtnrir.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxutpcg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcgzsbc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoyhclk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbqpzjp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2owtsqkjb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrjeahf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2euebovan.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyzemlq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyqfcjj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2orwqyitg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2miylmoyt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmejjlaf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmertde.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhptxnf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zeszblua.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmxvqoz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirghadg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uzndfsbf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sotycoxm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmxzjri.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoxlmfp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2avemhmax.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qerakuxr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ymouunyt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oaricoxw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhcdhup.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dftbopcm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxmpsrh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstmequ.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwjzggi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ivitfajb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chvieofb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzhvpbv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2engnhtcj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2goimuzpa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2edcxtgfa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvyzwej.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2akarimoi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2higcmseg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbyzipi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaltnyk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2potexuev.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvgxare.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpkuxho.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqkefqm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sgscxryf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgvvptp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxidgrc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsfnlke.html


<!-- 参考信息 -->