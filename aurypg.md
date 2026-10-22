代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsntqhw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2taxwgkhr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpeuewl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyrvohv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwvpsxo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgdomnr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjifcizr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hicvtgea.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuccexp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fozaekev.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpseooz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2swpuasgx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2etbxcvbx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wueimhoe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiznvuf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cepaodcr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfgpiuv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqmlqdp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2czcnfsxf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyesqha.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rclbbsvj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaenkfz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzxvywb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcuhhoq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuetdnd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buegssvw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeyyslm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gclikhvl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhvjgxm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfanweta.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkfywrj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcapmmlb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfqyrty.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxthzoqi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wucgttuo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmxzhgh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oghltjjx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcghabk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kamxefgs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmxbwmg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuxtckz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wwappvwh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsecrqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anvesvbv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swutdzkp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2klgsveui.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmexnedj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsiamtr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yydxuvzs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnaoxuo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbqohgd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdfrlnj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2webfswqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqojyqlz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bsguvgjq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfxuskj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtnlxoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dntytswu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnlazjh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2noldlenc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2krrjbsun.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arwemwgu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2flcjksiy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfdwynf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2docabzsp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2stbllswi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2deolnxtc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyelfee.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjmdckn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvmnhqz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdynazsd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlvnkya.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeubifxg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wugtymzw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqqlduw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqfmhgz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwosgugp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyivsrp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnawzjdj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2atfaarzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwivvgvo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nsotijtz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2irddldjp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgsxcnb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cximywny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkmeajz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgiuqjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkuixtx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhgzkig.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbtkumz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sssrhulr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aweqchcn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjpvbnw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kckwtjdn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zudqyjaj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuqbada.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2opatadrl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzldobk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hquixcbl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnbmnck.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mhndsicg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkvrovt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbidgjr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmaybhb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwlzcxi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlykbec.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmencenp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfitvmb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2crymeoxi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlzrtxe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuhgirk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgsvgfr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqndjnn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lebgapvg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxqbwbt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszjpvtt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qczodmqg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwharler.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkakaunb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbgzgyt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqubmdl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ukczcmqm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2roidahce.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pknkvlwr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrduxop.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucekwahk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oplswwfd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2khohzjrs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptifusmi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2akdajvwm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxvdfgw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jceetruh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqecypt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2clpkxqpj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2asoxyuku.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2veacgsyc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2januigrd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjxqmch.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnzsjrq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuygzod.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cccagxbb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ururxrde.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2splhwpnx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtftcukm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2euharraq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbcwomc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pievzjya.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaxfxkj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cktyuyko.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iodyeadk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sknpcrty.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrmmxte.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiwivaa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcnefro.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnynykai.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gizsgblv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjczhue.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2czmrquhc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiywhwv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2myxfjrvy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2udveodst.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzhmeuz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdwfbkq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvlyosx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjyqyj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtptyuvp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoegern.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmmcorg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sltfcwvc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmciwfoh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmlxorr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmnqgpv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwlxlmj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkocval.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jemnfnlx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsutaga.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhizcdx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxpkpsp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kpczmfvp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unjgbghx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yxehiead.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqocfgwc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwyqwpb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvygsegq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxivrgx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbihifo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuuxxui.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpkduej.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjqpaio.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tuouznxd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2usakxkve.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpkpvim.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuznefm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdboknd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezurtclp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2keavytct.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfmojvs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdajksy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzkduow.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmisxxga.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoronow.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjzyinm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlwlage.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyfxvoq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwikgui.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvpqtpu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2crcjcjhs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rzulriyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2djdeqaaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxzylkq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebywkihl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edpsirdy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gegoncre.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qgevksxf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiuqzzl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scgfjufn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2czxdbill.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsfxehk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsfftwj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2agodcmqt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdzxonu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wabkwcwl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2litjzlku.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxepedrf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzfbqlz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqavjwv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsfqago.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2htsncabi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2slqsnhne.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzautjno.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lojsjzgv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggchafgu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtndvoz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxegwuc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2auddkame.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2exolcbuy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoubtua.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrqlrzk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbputhuh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwvekof.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeehfnl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvwbmiq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qxopgiqx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuehedy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2meykaclw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbfusio.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvsfgbo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnenmsxn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeqyeew.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kllhveck.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zlibhgqb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwppclbj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2igjprrwj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgeioyw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkynkls.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbcafyn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfjennv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfjzwdl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uyktpcvj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2varyczfx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uloswkfk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqissiu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaslpto.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mylbckha.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjrcjra.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyfgadg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zpztuhgg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeojjoh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbunclp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lltpmhsb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lwagftgk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhiiocy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mszbzcwm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oykzubsx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlishzks.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qyleafcr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2upskollq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkitgipd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqgtqeq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aftshosx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gilnrxes.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnfquhd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uegyiprd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xysuuzpo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoozabn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvlqfyf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2thpbpaoi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdtukay.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmuyihy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2faajgtjx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2usptjnjy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmecelg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2khskeccw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhafitc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fveiapgs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncisphld.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jelehbwz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiiaihh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpkwqyu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxswmob.html


<!-- 参考信息 -->