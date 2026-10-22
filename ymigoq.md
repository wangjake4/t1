代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkyqajl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rweiarxc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlnthfd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzzvnrm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmipkrbc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgwnsjz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuftrfl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sngmhtid.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2isvruoeu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuugqnqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvzlvpd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gmisudjd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljxrcs.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvrikpf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtlnoqh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2husftdos.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tufuvblk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2omhiedmc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2plrefhqy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbtyrkp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxyxijn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hthcicty.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qamazltn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbzfzac.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzkzbmj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtenien.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2atgnfkqa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svjrvcpj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkoybbs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjktuhr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jctkgaut.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2whxfvgtr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xvehkvzt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkortne.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpotofl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izlwtrpz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnoocsh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mctbmnmv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mvplkqda.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sligmpzp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tnadokfw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzefkdpe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iffktntx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtytnrd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bijcwvhj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvrifkw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmwrisl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlliogg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbacjdbh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2klhnktki.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsituuv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbprnuia.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvqzcpc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjleeho.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gcljmnli.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdqqguy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sppyoihi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyuuets.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuezjwy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xougsill.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2soyumyvi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lshmbire.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfejsgmk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oguwceov.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdczkqn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpkzilp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsibqkx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxunzzy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvkljx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ossyclwd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgxrdep.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aospmbdq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luhdwzin.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuqadwo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiysvezl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxwjqxh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2llxlmefx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2llrhocxa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sicojoaa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2swgsonzw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inovgikl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgcafhw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuigqmlf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzrfhe.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hytgczdu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ybywlijp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2njmewosq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vdspjzub.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aidktsyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yetzrtbh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lavdqpda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idvfxbca.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeijyoy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrvfira.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcefzzw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2svivztlv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nomkpfwp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2auutncgf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcndzqa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaphskh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwirlcbw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrvjrbe.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2egaddfqn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwjcqgp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zxijbhmo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmezgiv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbpmvvv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2auoosjjr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quxnzanh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbzquep.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeitfmle.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2idruvjzv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwvoegu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvovgyxz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2idkjjpxj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfemoqau.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rclzpqwi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2baksuwnk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2emygleoo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeyzyaa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nklkuxni.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvxbdhr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azkqwawu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwbxagx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uokakjjd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2glkmsfci.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqeszrn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2anvunccm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqrzwqm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxeyfck.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lrldnjog.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqqecvr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2roxqjqdm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvnvriy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2duoemmpi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkkzmko.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgdmjnt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfpcslm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtcthfo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xixrncxf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2unpkeubz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrwlzgg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2esxgwyiv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oejbcbwr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2whskkjrj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kklxalwy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2igsyeuhl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqtxhby.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfjowvq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnbbnyx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lanrppoq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2khzhjdmn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xguveifo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqbzwmk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvwfule.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sktpqgsm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2csiacvbc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sznntxox.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkjqwzz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2maadzfwe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvaidix.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzwtnup.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvroyau.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zooyomms.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjtigfk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zllcbboj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaqwlch.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiomuiq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tpntcejo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkubwusw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkcpejw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrlpsoc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiqyjjk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2suafzqyo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwyguse.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2opjbguou.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlrgtpu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2owydfxia.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcphipwy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkgtvdk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umbdleqz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlgwivt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tprqcazx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grenyqfv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbdcpuc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtznpmyh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjakjto.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2karkmkji.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tptxonxf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvzuqfl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctetxyvt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2seugxevh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dktkxuez.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyzgbwp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrqoadw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eimvahyn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxaktnn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2trajnazd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqyhnaw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2worwmuoc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2simgkbez.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdcdfju.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpzzodm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnomrmr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopgptga.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ygacgamu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiqbzli.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lhabzkph.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2upfsmkpc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbczlwa.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2saivazkt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvqtvyw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2clgolodw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjwvvra.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuntdxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcamrhv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2urjmuneo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dftoeuzq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zcksxdil.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apawbvff.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwhgnqk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcbrgnz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lalmqtvv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpzlnvj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpmzzkh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgucgyt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgturrl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rddpexjf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yshwskix.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2chfcmevs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qyehdehn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxmcdqn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vihoshxx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrpwrhd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwrpsyo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jalpexpa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2soaylukj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhazaxp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plotgjfn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtekzdrg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqumygc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2epycbgdx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uaugrame.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogxtsao.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wswlljif.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjldmfi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2emptoiyq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbfwyew.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2btalitmc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqrdvhs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzqxtlc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tejretpi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2twhmjytm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmafjfhc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkgrdrk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cozgeqtk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dunfqybv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2frwcbelm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2glophwto.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsirnefs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfpezmt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqlpduc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iehvhpgz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnrqbbj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zznbxwoi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbzapzx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwaamkj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaeucvv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2petujatg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsbnync.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ctalmjfu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsyqqtm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2czjfjxqx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tapktfil.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtcjwgu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohetrkfv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ignzwiys.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzbzxbw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqwvwtm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuiwfup.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeemzti.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdnpfkf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfyksyo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbzbncz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwrlghh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tumpwrai.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nszdixxo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wapevzpo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2azkqvzmz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hciafixw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2biltckld.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hdecyhzj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2armqrasp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2blostmvl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxappzb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiygihf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iohragow.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gsobdanh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyekynl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvesuybr.html


<!-- 参考信息 -->