代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpazlao.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrwmiud.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2glohkftl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fnghackm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpscosxc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvazitxo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrkcdae.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfpxool.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vulfjifp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vcodsyav.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaowhhkv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mfddaewd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnaluxe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbtpgvq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2afgembqr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvrwdhj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2orxulypn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwydycc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbszcens.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yupwsjmn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rluzlshe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rrucifpd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxkwxpv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vnshqmmd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjctpzp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2embpttec.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvcgana.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyxpajn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pbidmyny.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sexqtbrb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zypvuttw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuivwad.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwvdxku.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fivzblwl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqpwcbc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rezmpsxn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2srfgyiyu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yllvsoih.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdegfjo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iskrmgqg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2outmrivp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yufvbcqb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfikmpc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqoonop.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epwzfpnt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scqmwsde.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npgeifae.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvlsjaa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuyhzdh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpjbknb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2grdrvqgi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwrqkdq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gmasjbfo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmhkkij.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbhvqpu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cufvmucp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeitxmh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdxdzvd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luaichro.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bafmmatc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pblndqmf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvitgne.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2crbxmrai.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oomqoujn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2clklteqx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvulcrn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uahalvmo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2douvwxlq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxagqkc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fkonkmsu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfwsitk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpvdgah.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jotacmkx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlwanue.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2srakrdbw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnlgndq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnusbvtf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsiwptn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqorzie.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2olharkwk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzpxfpl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mpldyrbu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtgzkhw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yqybbgxc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iytotomg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wywrimxg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wberwjmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgupmgu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xibasqnw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjizfpcg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omzrhiqe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnygcya.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2smzzcqpz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejstapzf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2etzbbwcg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfusjdaf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2waniurvu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2caacdkgu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnxxqfk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpbzkfm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqtjarm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bumekqru.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2alyjcvtj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxfhfsb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enzjgijd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdkvulx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aynzblxb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhhopgp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zeedznxc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oggmvysk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2urrynaiv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzygysa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgagnk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cesfquei.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxwkccl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsispbr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ktonvvai.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpptiofo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfndeffy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jybcyjqs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sojsvkoa.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okmjnvxq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2stoqevos.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfpqlmc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpdguyp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbztzud.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tovbaxby.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2shuloppz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zubndnhz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuputqc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gckvswif.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiktzak.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dncjsojt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djiyzjhm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tesvjkwz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfibwdpa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2afdrgffc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzppgbjm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsldail.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2davtqnhg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlpyhzj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqutpuj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pejzvyof.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxprzvr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2byfzwmfj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkjywdz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmvgalv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydphnsyq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tafczgmc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibappycy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qifumsrf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sumxyzwf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2idzsgjmw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2auzwwdip.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxjhkis.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zoauzmwz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdvcdqt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsycutt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxtssrh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwpiaam.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2thflvhsw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaslhvcx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mflxlrbq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzmfosi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2clcynvwe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgilmkk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxhgfch.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzmemtf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgnrquz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfvfgzg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntazefrz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mddvvabf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2quccyoki.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2icvcxifa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfvoqqj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpufevlc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jhscqvfs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiobfuas.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaznqpp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeunlccd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqrgjvz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhblqkxc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eacymrdc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaktbbqh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2miaxxury.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzalhdjw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvxfcpx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtsdhdi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkibvifv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olexnbmi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqubdrsg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzelprss.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rakvumvm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkmqjgd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2afkcxnls.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axhzjsoq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyserypo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpoiuzb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtjxuqv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tusojhrk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwptqytu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdelkzw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqbnpki.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2krojwywj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2egfhyhdx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pjitparj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2smvfcfbn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wbquilqn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzsggig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmntgsiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imfnbkps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isnzxlew.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeynfjw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjuicb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvcivd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2unsqcbfi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzulvtg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdevigi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2djzdtkys.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2thghvrel.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yijoaefk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnlwuwt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kufelrli.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqupxtv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2azjraebn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooglmydg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfamtxoc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2srbcwglv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyqnxec.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqofjdi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyjgupd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrkreli.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuruphq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2apshyybx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pjefgats.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2narmtwkn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnrnqtr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfhgiyf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxkgoan.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwkzqln.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaogzek.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hepnihbr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2korfljox.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuojcca.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2muxwykib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojidslg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtegqzv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2asyfodsl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfqfcyv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2itxpqtlv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zyspkjdq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzwlvmz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2auglpddo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mehoduhh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zofgvjdu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxarjwdg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkhjwyf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2npcylfgz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwrtmor.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wewkhbew.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mywffhrd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2soecwzlw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2txnxepon.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wctexenm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uxulilfs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcahfjm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrdwkci.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2skvrwhup.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bepunaht.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtfmook.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dolfvtzx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zosnokmn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxmssra.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2selminpd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyvcixl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kunxpxzt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdkqxiu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pesfirss.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oddgtjlw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsotjry.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxdzweb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwvyhyk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uqblbtoy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwisimto.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvxlygy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdhmrvy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsrlnow.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2llwzpuom.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtpjfel.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2brtquwvk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2loubpteq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszkbfd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxazbg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hiekfjzx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ugshfxmc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lecjwvoy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2keqjngwg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjclkwvd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olrhrspj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svjrwdbz.html


<!-- 参考信息 -->