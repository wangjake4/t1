代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2actoymtw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpeirra.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2unoouuos.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlasqwr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cclfgvtl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcvfmsm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzubfzp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpxejrb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqvkyxo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emmxkegm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2doasxubp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxfldvk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlcvnqu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrjbwpr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2unrmxoxa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyribrd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yifseavd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeyjqzs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jypnukrb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbcbrbh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2muoiiqtc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwjpryo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyfegjl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stkzkrmo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xolfifrb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnipwdek.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxlaqxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrempec.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyczycs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoqbwta.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2seifacur.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjcjdts.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdxxbsp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2miqehnxm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxuerwq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyputsmo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwefrvqj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcdclkx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgxyedr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2toregjnx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgccynw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpldwwqf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhrnqhz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlinekis.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xerpwnex.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcvgoyr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tamrhvmw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfxbowf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wholrbnc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuzgoep.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoshpfx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqbefok.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylthghta.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiahhfu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mjffyzjv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vttksxlq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nryjfivc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wonognyf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sudhtpfz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbslmus.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bciygloz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2inksefmt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2umekjnzc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbnydwy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2whnlcaue.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jalzvhwg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqbnrqo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qadhnbdv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oruxyvhe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2abbbmfca.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhggsze.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ubojlqae.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrqhvoi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqbkeaf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgfzbhi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjkbsba.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoadmsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpznpcs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyjwlwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpzavvd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2flfkhxdv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yixmhkvp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqygpyx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qyejnbjz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2frejlmdg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjmaotj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaxooty.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2scwjqnea.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhunojt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkuvlfo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hkftboed.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxkkxxx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2whirwnpn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnrsiih.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdqnizn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2afstmtqe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znqrhlbg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2osxgwkku.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eorejqpn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtuozxu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmkavxk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueooszqz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rokpcavi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2joyuwsdt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iybvmyio.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cywuiirn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lugfghrv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eouqscqt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hequzsjr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2odbfxchd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2keinxtpy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aburityy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfnghdt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxdhlxr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyjgurc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtywgydm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cclosgqb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqdnxsf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2soxrzzgj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2obntzkpy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2piscimjx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwtirgs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzykyph.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kknwjdhc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cifiyemr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2atqvlzcl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnxdwma.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2abygosnm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyhdglf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqtibia.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpxabpa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdiyfyj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgohdvqe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2trcqdvui.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxbqtwt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlngyell.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsttanf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2otrbgwgc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhujill.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2smklmrkj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwclyde.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wovyjxou.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2msczloho.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlyqohf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfnsfaw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbmdqrn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fntkpjry.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjapleu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kteufknu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzxjrjo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ockrzbpy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxdnnim.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpsnkqe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aojckqgy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgvrntp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pminnhvj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrtqlgt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfggrbm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgflzha.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2khnsfbhq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcwtgit.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxyklqh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaukcec.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmqdzwj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uorqbrvc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2znffvvnt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgafwra.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbofyhm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mllviyao.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnjsakq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbajuey.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eshvuaag.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjletnp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpdwyxt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsteleyb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2itrlwlcb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rodzhdoj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uesxnmow.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2naueejah.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqinxlvo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnoonkc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owzdzzxf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdaphoy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnpxuug.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fivrrban.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvghgvk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahojulnh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lvizwypx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuwbqpn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyspaxv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoecwobo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuvouxh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyjmfva.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrehgml.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmyehth.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrvelqe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzoqtxz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdcdkkx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjbdiws.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2surnfdsc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtqgzus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzhkhpf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvambps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwshdujt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsylter.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmyklyu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mybtbbrk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbgoadd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbgblkj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bduekbjl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ypickmco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nutkzxmk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2csztuvpe.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnbirlh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuwnbua.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqyfndy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhknkyja.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zynjasgf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcnhcgr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxvcftv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cewkthft.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoglrgd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jfodpnrz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fklzbpzt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2txttualb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfemztjj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rznlvpus.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjkrzye.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nahckqui.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2twcqelrk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sizdvwga.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsqcury.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2onvjgnzh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgmaaeo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yibnuuci.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwnkixm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdsxofm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxvvguy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgfgtih.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwdroei.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnrudri.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjknbip.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dhksujcb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwojykz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2etgzbvdf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2muqgpake.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2djpbvycz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjfztxl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbhwjgg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2udvvjewr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlmvimj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfufxmdx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyrctmf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bucpjmbg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkkoyrx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lszyzgpx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2miewloco.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2okphigyc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrgevgi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkfnqyo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjethev.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhqlznu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jfampvbr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiynyxh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2utsadwcy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqgxwle.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpahcyav.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fykfqcyv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmfrdpz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2spksmjso.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2twfnpwsd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhzbkvy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjxbff.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsczwcue.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2spiaswaj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2efdtqgdg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gkerwppe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoqkiee.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uptshjab.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrzzqkh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bptxkzyq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxmegcr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fkohiowo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2glmtpyri.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vxygboge.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gexhpfth.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zaacfdpc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkqwynu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfcjsiu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccudhjgf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfcxfyo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkzdaor.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bomtvtmu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgzlgpi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgvellt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2frljdimb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcubeftb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvjivdt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oibpksjl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgezjlpm.html


<!-- 参考信息 -->