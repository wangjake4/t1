代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2edtcxerw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfvrlgj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhesxxk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2oagutoeg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjojndsx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcnhgoz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lntgvepr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuozyof.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tebbzxux.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfyjffj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2atiojvdd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2npktxdxq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekavjtvb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfkvpfy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iftpnfap.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rprhiifk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvfosdj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2shwcueeh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmuumaq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aeolevip.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeymfauy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2znodpdjm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cklbrjdq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lldvogit.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgofhgnr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvsgblv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdzchir.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gndyuezj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oouwkzoz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhqfxjh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2blrbqnhj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrkxayk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlhnobj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsxyqek.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbsilpg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfygsrm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjkyvjn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdggjfko.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2limxebvy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwbzrcq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjofewl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkihkkju.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnudpba.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usqtuxbh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhcvmcf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgajpxn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqlwzlj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqukymwy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2piropvfx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqlatny.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwejne.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2motadyiv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfzaqmc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qaynzyzw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gekxkwds.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sasgenkf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spntjbon.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tosnewgj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dweypldh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihsvdi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvejsng.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgbyinr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtazmaa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuoubbp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjrulav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvexeiic.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zecbngdk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsslprnb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxfszav.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopgihku.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnsycsn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjdvfey.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdppjek.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwivtdv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxedwwti.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lwptawie.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpcshya.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iprxroxw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2skvazctj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwceygm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgelaoe.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzefjjzd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2agziaojg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2plmbcjjj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnaplsj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sunhmara.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoucsji.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2limvbias.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzntmtp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2frmfdjuy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypffgxzb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxgzavk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnclzfyz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wiagkywl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbeitoz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rneguime.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lkueexfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hervxzfk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xizwdszt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmepaylr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhxbthi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxdnoiq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcryncy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2upvfeplp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eommxibg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iosbmcwu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2sadukbdn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uaimsnnp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhdxbwy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwokqpy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kslphran.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyalxeq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iyadpigk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwceksn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgwayqw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzzqrft.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2siofnjuv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvhdarw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nngylmho.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ailksfkd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbwvlqc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2egyjgvas.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gihwreqz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbkdsto.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuntfue.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2daktjkff.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kltgfwcq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdclrqmw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wdugjtnq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuydgpcd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2thmcboyr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuhrzlw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fduqmprs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmemnujv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yomquubi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkotytxn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fouueoys.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezotyikh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2afwthxde.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwjodqe.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqyowyr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mswtbpan.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeqzqbe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxbexvu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vskpypjs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2locetgqn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjjifei.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuguvsrp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqrhbwe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceylspvx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rtucqtxi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zogvluju.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiftavt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2skrgzauy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcsaswb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiszgln.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpuulde.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhmktvy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pblenzyq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaqdmqo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbnrgrt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfdkgha.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2klwqftra.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qesvkwdb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gebgjcdd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eceaktun.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlsmudg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2shzwwxze.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwbkrio.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utpthgfc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsqpgfe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lixccmxq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2psxixugb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbpdbnw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2twlwqehu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcotbwnw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rayutuwc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eazhdtgs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2udkxcqnz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jnljzedk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfsidjg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ooziumcc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2abvauyuo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gasjcwur.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ediqpavn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwuyrps.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2quuxelgs.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuflzoj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcznlrj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxeacs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pkswlmft.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krcaumfz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bprqxoox.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmzywvu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqjvkdx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpohxurm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eteyfuaw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrpuxxs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2taakbxga.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvrzfeb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xomvcnpq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hiibdtqf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2paeywjqs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvikamj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgklppwa.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkisyvoi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsjmtem.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvdsfgh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfymdtdt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2amztkdub.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuqtqda.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlrcydt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2amiiguqd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2azbusvmi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hihvssqh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eswamozf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrqcbta.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoofijd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtiidvz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gzacyowx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccplyxdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chryqepq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhdysss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hknvspzm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzntrhx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2inpkyhhg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2shsqmnnt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xdegxdjb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwamdsu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejivnwpt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzkefno.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoccwmk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmktkvme.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcpdkaz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgtvwal.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbawjbn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdkbubf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hklnjqrx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrccjcr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmdqjth.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwkzdec.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cemqtcdg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxtszoy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgqkmju.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2otybdnkt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvhsdq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiinzvm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtjxdri.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgixxra.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlbaupa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ftokmjqb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eagokrdk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ltldnsdk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2raquardl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eubygkzx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxnnbsy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoqtohz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyfznsp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyukhna.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzpojva.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xdirilpc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnxfmlx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zizkfovp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2guinzvuh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2umyrnwhk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qyogyril.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dazyhqlb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dctpuzrf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoznxej.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xweewndi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2otwknlna.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpsapjo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fwudhvzg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wltlryoc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rquoxrna.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfenxcib.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxjtxzi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2asfpyiqe.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2axxcruns.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyprszm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdbyifr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yocgmatc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uawfdrcy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrbjstp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tviwshsk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlgglkw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2phlduzhe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pvykkhwv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrlobjv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqiwrmp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ungtxxwk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktvsfcs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxaddhc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2afnigldg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2avrspqug.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyhbuto.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdvitjr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhujzyw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fqveocal.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsnsjlu.html


<!-- 参考信息 -->