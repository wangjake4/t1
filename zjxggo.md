代发 wailian999

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gthkrcxduq.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtecbhfedx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtbjbbjdse.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtjjvrnbor.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtpqncowic.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gttddrbtvi.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtrccaehka.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtjqilmwzw.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtmjwmayut.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtnzcljqzl.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtxlhjftib.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnuzhinr.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqvsvutw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gtbtejjkmg.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtdjsmzsnc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtfibbaovd.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtlqrtived.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtlxcrmals.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtlmivxwzi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtywdccgvn.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtfwgjmvom.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtbryftmob.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtvgurrmai.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtsyszhouw.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtxmqdjxjf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtxpryaswc.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdibwkrt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieneqjkn.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtfjkjqhby.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtidlwlbjr.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gtsvbqxlfl.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gtnurctdkt.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtbvgycpjr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvisrdoe.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtunoamfoj.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtkqlmdged.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtqtollzue.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gtridsncvf.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtpmkqaxdf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtfbpfyvih.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtymllpeyk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtymkyhyll.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtoujgheir.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gtxatjzlcf.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtnzrdhswr.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gtnoxdxfek.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtflddwiru.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtoabnwjlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtekmhxwpg.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtyzbbznuv.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtzghcrnyw.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gtzedpbcgy.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjzqaxdnr.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtpphwktll.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtydxafetf.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gthyigzrks.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarnirkke.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtkkimrunp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtvzbrwkja.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtnzwswenc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtrmcrqvkv.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtrnrmaujv.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtsugiyqzc.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtmjlskofo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gttkewkndp.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtpaqtrqee.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtjdbjbwdi.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtdevtdyij.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtkzgpdywr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvhonbory.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtxhjkpjff.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtaccgrgsn.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtqxkddaan.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgspcuqng.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtxwylfmoo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtbcjxggnm.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gtadcarbni.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtwzpgrijc.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtwvlgcagu.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtzdxcghkz.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtwhnklqnc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtoysyxkpe.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gthpdxuyuu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtnpqjtrsq.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtiduyuudf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtuyvrxnby.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsfoyerb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbopsqlv.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtpddjcnws.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryzfixtg.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtgsworlzr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtvbuzfakj.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gtfiydtwmg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gtqdzqedki.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtbjhbdjmw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtgfswcdzs.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtoamxhrfy.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtxctqxzwo.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gtzdehthkt.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtdpkdtigw.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gtpuylrzjf.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmipgvzeq.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtlvvfjqof.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtsvufuhek.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnphhhyex.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gtkigfzmhh.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtxlcmiodw.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtbmemuwmq.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxlyoaxh.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtuqvotfhe.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvzbczbg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gtmkscnzms.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtpthfqomo.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gtlipesber.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gtxrkokmbw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtzdwoynfy.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtulzaimlh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtywhxugod.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gtrczrlyvo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtxxjbzrpw.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtajvtwcur.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtmvvgbsgk.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gtkcmnnyid.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdelchnvc.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtwvuyrody.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtogbovnqt.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtgsimmxvj.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtrbjcaknf.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtgaftciis.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaowzarw.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtsahxpxyd.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtnujmfdbm.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtafqhxgqn.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtrbadvpnx.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gtxknicryd.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtgrciixci.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gtglhuaqno.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtgjecpdtd.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtpireoebh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtufrqglen.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtiujboxts.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gtutdnwkrn.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtihbbjxwz.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxuryjuv.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtufxyubsl.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gtktonrazj.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gtnmhlnyvv.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtctyqjtov.html

[T39] Lua：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtekzfozsj.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gthygghdjx.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gtdllrnlao.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtihaddouz.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtcempkmvt.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtlofsfjkv.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtevrvdoln.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlemhpufh.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtnxmykwth.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtgkjwpqrn.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtooalisvp.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtfhtcqlpv.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtzzpnhbql.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtiswvmmbw.html

[T46] Perl：哈希操作
来源：http://dali.pycfn.com/Article/details/gtbehuyqlx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gtwbzavxyl.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtmtlvoabv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtahxluyba.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtfuwjcwkm.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gteqqzcijh.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtkbzglemc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtmmljfqlx.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtsalxblba.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gtzeflmesy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtxdajatmu.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtyzssivay.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtyqcfmymd.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtgopomjyt.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gtgeuscjmp.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gthrtglcof.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtdbspjlgl.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtwovszwld.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gttmntdvzv.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtmrvwsala.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gtfsikwxjs.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gttmgqolsz.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtqqvlbutr.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtmspmbcyt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gtxvdkmawb.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtazxpariw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtodshraxw.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtxricnmmo.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtcvqmhlpe.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtpxwqijqg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtcibwekeq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtefektslv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtfyyukgfy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtemsvswdl.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtvokfcoxq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtussdrezc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gtjhmzpmsk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gtmbyfmuhp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtiqhpdlda.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gtlrkwofml.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtypcclgqo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gtrknsbiws.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtkfmlntnf.html

list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtyddnvckc.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtvxparxaz.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtpigjkuwm.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gtndwzwgrq.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtjupmvelc.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gtqhswhtpb.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtrvtvtxkg.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtzqnqfvdp.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtaegneq.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gtxgmbxpua.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtkirunqow.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gtrmyvqmfc.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gtbylmymwo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zdqjudy.top/Article/details/gtumldloth.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gtlepzipxx.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtqejvfytl.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtsaccuwtl.html

[U14] Py：分组收集到列表
来源：http://dali.yangfankeji.com/Article/details/gtfewpsber.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gtxwqmluqo.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtwsjfvzcp.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gtmiodrlas.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruyuxuuf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxvmacdj.html

[U17] Py：初始化日志
来源：http://dali.hywenlv.cn/Article/details/gtckvnxqrb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtvbfohzwo.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtipuxbyam.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtzjixwnyr.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gteywlvkwy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtlafhtawe.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gthvuhrdbi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gtbrhylmje.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gthblyjodx.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtgdpjcksh.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtghksdyhw.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gtxvoxszzh.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtxxlznbva.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtjkrvequl.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gtxavniqyu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtlnubcbeb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtxrzysvcb.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gtotpretul.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gthjdaakkl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gtakdeopml.html

[U27] Py：异步 HTTP
来源：http://dali.jqgfzy.top/Article/details/gtuzwrfmnv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gtrnlqtzqz.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuigtsbw.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gtattbojft.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gtekuxwexw.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gtdanvpphp.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtyndwrimp.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvzcdhjg.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gtzvhcbzga.html

python -m pytest -q
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslyqchkq.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtuydjioef.html

ruff format . && ruff check --fix .
来源：http://dali.zhongyouzk.top/Article/details/gtspsyscnf.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gtnlvnhhtz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ehwqpu.com/Article/details/gthdkpdlmh.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtgmovzzfm.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtqmwhjefp.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtiafpathm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtngfgnval.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gtzudqrquf.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtcvvtfecq.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gtxukkhbtg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gtksocjepu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gtohramkrs.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gtwecilfmu.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gtbuzufbqu.html

sys.stdout.isatty()
来源：http://dali.jlsjyb.cn/Article/details/gtpjccoihc.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gtxvrasyop.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtlauqmpco.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fengsongda.top/Article/details/gtdnziryga.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.haohaochexian.top/Article/details/gtnxxkjnek.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtalegayux.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yvedp.cn/Article/details/gtgqfhrima.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gtqsooiehl.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gtbzjtxlvj.html

[U44] PHP：开启严格类型
来源：http://dali.yonumen.top/Article/details/gtyoqqdckz.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gtpwriwbdz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hammf.cn/Article/details/gttlcewikl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtvmaieyjs.html

[U46] PHP：可空类型
来源：http://dali.hnqzz.top/Article/details/gtgsciddhz.html

?string $name = null
来源：http://dali.zhengqikj.top/Article/details/gtycbavkao.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gtgvkhccui.html

int|string $id
来源：http://dali.hammf.cn/Article/details/gtmqoqovpe.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gtvucpvuvu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmeosqaw.html

[U49] PHP：只读属性
来源：http://dali.yj20258.top/Article/details/gtedxevndl.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gtuhsodmlp.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gtbgqomwfi.html

public function __construct(private int $id) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikypkeqj.html

[U51] PHP：数组解构
来源：http://dali.zycfv.cn/Article/details/gtnjwmgddw.html

[$a, $b] = $arr;
来源：http://dali.redwolf501.top/Article/details/gtbddnfaov.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtlveidmbl.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gthgtttokn.html


<!-- 参考信息 -->