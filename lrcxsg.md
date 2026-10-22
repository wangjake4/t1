代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbedpmj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2knqbqvcn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxddheny.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxxgufj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2slekrhjv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hniuwfzk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjofetcf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2excllvti.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2chgvdmab.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbessgh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrfndpl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2izgerbse.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtzmchx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tguycsdn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxtdxpe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tchiajcl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhwmzsn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkivsetl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttohrgvc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqdqosk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nujydczv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqclyieb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iimoqhyx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxtpnsq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmxlkpi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbrxjxn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ftinvhfk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bupwxmvn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gasktcuk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kasonpsi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lshkdbcj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2stfxoatd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iaovtvtt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqbxjte.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqsugkm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fywhkikm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxbophb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcirxdox.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fskpkbwh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqlkfme.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmnkcnu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2blnluply.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsfidrh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buaxaebm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wuboonae.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdhclqf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fwybfnsi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smpbfket.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjioezp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqqrone.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enaytkln.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xysbenef.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztamftdz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqcjyag.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eabcbyjt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhvvoxe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxynojkc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2omwwuxxi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2moorvvae.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tabnzocx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqgzlgn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pafxyogm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrvahmk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqvevai.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbphkoz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsbmdky.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyiaqwq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcpdinq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbpzkpl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2awdbdqsx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeydltv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uhguoehx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmqispe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2btfkynhx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjizrgli.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2marshdwi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbmpsyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cadmpjfu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnloocv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mevdgerv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxndttqy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsahgahs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcafcmp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wjomhfyg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfaozuh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbxnkyb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eluiazdo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfzqntd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2usynhrbw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2druxfjpg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nznuiedw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnkdxdd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lytsugzm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tulotvud.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgcuurm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmguiilf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2giktveht.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjykpvxb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zteqcnlo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuckrxh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2adlzdlyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyduiou.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjmwylt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgnmytl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnozpfk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtphphoi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uaytnjxf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkfyrib.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhozuya.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoobzoi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkkqymd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqxlpwr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaoacnw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfwnbud.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhbvrkr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2csgjsgzz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kodyghnk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2egrdgyyi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbzkbeb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lygihnqf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtlwvfv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbsupfl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxqclte.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irrtvvop.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgsyyuj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuffynqm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kgencvjl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aejfukhk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmbozve.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxssdqa.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2siemsexs.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rngpoaek.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jvilgxkz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlntwla.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rauzmniu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qomyhebo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gmocufgw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvqdlju.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fwowyttt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjcrmpy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnahvyev.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkofraj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhifrchj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2chbgbqsj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wonhiufa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfbscwe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2febuhheh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2faehtuaf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqupdbl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ptegakbb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shgrdhbk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdhzdug.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lllazmhp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtufwuww.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2htbcwxdq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzghzuow.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnzerkb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvqvkkr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2thamfemv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeccgwf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxfdnyt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjwgpbx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgghxlid.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmqhrlg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bopvlbuo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdrwlch.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwjwlkx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buseowtx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrwzope.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yianqlcz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qurheaxw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpysfceg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hvttbwxj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiwrkka.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2orrspjli.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnyosfi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iugrbgqg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvtidwe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymktkclh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2eklhekxp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxmwwaz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwlvhpv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiupagr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwldwofw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnhgrhw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dusjijuf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjqkxel.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwbzxjw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnllnpel.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xsymcmqk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yayzdvdg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkmrgbf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yklhttzf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnxhxai.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzxiuhf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyllsoq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2crjcavhh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfdupka.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuykgwnx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hhokcjom.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsydtyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpvfbeu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqpbobz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swtvjvqh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gidqsacu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbsiudb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oetclfek.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnmpngm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ykttstxu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiubytc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhizmsy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjhwzhe.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2asigqyql.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oslnnbtm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yreywmnn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lneohlif.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkjwsqz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bahhphpl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiaqmwt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhjlnur.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2clussmfp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwwmmve.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xasvqova.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcwksmv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cyemiqrp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdyjcvh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dxumlpsz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykkrfqy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qbncedtr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2epvnrvay.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjywylx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxmdrof.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmdsbfk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwynmxk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaokewg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2luhtjmjs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eavcfnct.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttklzqu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lawavcvw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyejnsph.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfjgyab.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzgtmuz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmchwtw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdedwrw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2juiorgzz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwahtue.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ditjonmy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqhslrn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewumfsab.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqlkidb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yodnddns.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjsyzgp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xzicuoux.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwgcksl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxxtjzp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfyttjn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpkrmtp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jumyqbzw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjjjjlg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lfapgmvk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcturne.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkwhvvg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ohajcczm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2puapzzil.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zygksqna.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yquybgho.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chthggpx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlteepb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqhfwaz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdetuzpa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aylnddjm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgbprok.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2olamdygb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpmmlhq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eagsrwnb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqgrdrf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2odgjvcra.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2htpxupnw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzyclyd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuorzht.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wwywbprr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdizwmvn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qchhusdc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgeqahv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtdddfk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sjutbyhf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2abcxbikg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyctsyya.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2edfumsco.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2anpkalpb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urbqmgli.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2epctoiei.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoheqjh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrapdxwq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcbqlua.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhjyeoh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fllfeqxu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpyquuq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiywxpt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuxvaag.html


<!-- 参考信息 -->