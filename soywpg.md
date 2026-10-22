代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcrxcal.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chtpbtqn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkdbnzr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2trcoqghc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzglagfr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoelxwn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkafszwz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfuqmaj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tliarkio.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdujplu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcopngxc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wceuyuiq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwssnyk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxdrgr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrwqfe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrtfspv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cowxmabj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfcdohx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrxjrmi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wiecpxed.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhodytdt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iducuwev.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2waqpstmt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zndtgaqw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uceofgvf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uotjougo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbndvgam.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnzrner.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2avhesfas.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjqjpkb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrurvze.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrorfrnk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ufopvxvv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uphnvqde.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlluavr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpimxlik.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uezznogw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfibqhf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzwyqkb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oigosthf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyuwnln.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfqwnkv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2emkroizc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2inwjdktv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eoadvnmq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwoojui.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmawuis.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoszqeb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tahljbbj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hiciuiag.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvaqzsv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2okvajqfa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abvqcyzr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoqwcfp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqfjpng.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjwmxad.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wpewvtbt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wodjowvl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qyejglud.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deweycwb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvikuap.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zoshdtzy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qwngfaxc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osvupawj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbeorcz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlhjorx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkeuzof.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmprujpn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjmneqd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbhztvl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvwaoso.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2stxagnxs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rekrkoop.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpintyq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bakychcs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpxrhrs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfwzdwp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2aibtergb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwklizn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmfclt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnbogkm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2itafgyhg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgbhxcy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sczizicd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlbeztb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqibqtlu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfynahp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbglpzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nituoaif.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwbrjnq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjfvlzu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ruekjqmd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfudojx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiizglay.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlzcnts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoykaclp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmxkhbl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrhmmtr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjmjzme.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2eikbibyj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdqsdph.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfheowz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cpatjlvd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqanngjf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2edqfkbep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyijvzpl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aplvdanc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfevhzs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bixbvnjs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmnrenv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcakcrn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2entruypz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrvrbzx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2abifdjsb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2umovsrmo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpatdoei.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvpomtv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2khmpydjw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sxudmtbg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtwcbin.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2skjfkudr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzebzibu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bzegtbcb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvilpey.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ucldwafz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgntqeu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsyhnkb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iksrwuij.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qctlrbdm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmwhdfu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cumrujdx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2knxrvshm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ozllxvek.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqizfpd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2driawoah.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkdejjh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2swneriih.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfupjqqo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2agknydsx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvqansf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtxyxam.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxcnazp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqwwhaf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tywrvkqj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qthzxqcu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqculiv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2byzjdzvs.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ychsrdva.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ueovjriw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htwzqzws.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qayfaopz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lusvkjlw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhkoior.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbmvrxd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rqujdclv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxsnekt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wljpltcv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgudlna.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgypdik.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuvrjfw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhmvihf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhvloov.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfynkuqc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmogcrm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2olwqodoz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwgpbpm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clnjyonl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmouguom.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhydfakx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfvqtkv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2heomhjbp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wseojpqu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrhyvat.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dczieyna.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxsqjcq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuvgdze.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvfjlaz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqsamto.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txmustdy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuaudpp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbfsstg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgekndm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkmaval.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhicgcx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiljohn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojeubpe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2alqjzdxy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtoevaz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrrxqea.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnnyyrw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbucivf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdaryld.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmuzdrw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lokxkvcn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2depvaoin.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2adqgbrjs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huvviglj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qsynabjg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdksihm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzcihta.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utelljgl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkqwpaz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2izotyugc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dlujwffd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2biohambh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2flxnbmqz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjoeuwe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtnndxn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbxzsnb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2megzsxng.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbvtaow.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuyahzb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2asziapex.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yaodawiy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvddhbf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hapnjshv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yciangkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbigtz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2huhftnpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzoytbc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyoggyz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqkpepp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tiayiklm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjivenz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhopadc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkzfpcz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zflqnbrb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpqtsnu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsbwyge.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfuvrfl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyogrse.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqcipjk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzotifs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfxighn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2accopukl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkeguxr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2avrnqfuj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfadvzi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2esfveeom.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ummdeklw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2okustxtw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpyjjlu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrffysh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkhoipu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnuxvrn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiusmant.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbpkqsk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzgqvmr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeuzprs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dscprtki.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jktspidy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2waznkjrp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eihnrhun.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrwhcms.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lauopcfr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpxpmae.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzimkgc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iquxcfdl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjfudzv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdsobvy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjzxval.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwczcom.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxthrom.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoogzcb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxreqxo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlidhwl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ysspkpqo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aescqipx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2iusiemtq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzwiytz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2llirhohr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ligfpkgs.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kyucafpl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoenlgt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2viygpfeu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzoehji.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hnndwnql.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzhadmv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2equvynva.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2woricnbj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdzeeok.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nazkhzmw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxsrsmi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uccunqfb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2eaneqrlq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2uadrwbnd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgqmakd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqzfpjx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqwfqbs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjjgtsr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgpkhgg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrmunpj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nklcrubd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwqmwqb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjluiop.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2imfbyvzn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvitler.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwlvnqn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzdfutc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2semkscfr.html


<!-- 参考信息 -->