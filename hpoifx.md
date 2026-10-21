代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtbukwhpcj.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtzkencumq.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtuslnzrto.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtxackpytr.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtejkxmpec.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtsfmsyrob.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtoydkfemk.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gtefxuhvtq.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtyieqqscu.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtyzvowksy.html

#endif
来源：http://dali.ivvv.top/Article/details/gtfqdjpjwt.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtmfcwguhz.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtbsfhgvup.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtxcysslib.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtvthuggav.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtsoabjwjl.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtjndwttap.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtifdrmkcd.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtsudingsb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtjnfuzset.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtputelkno.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtyjeqzdts.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gthptjdvjm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtllxnqiir.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtyupaiinz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gtjehrrngc.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtlpfdbsiu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtfmwpoilp.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtbolbpvqy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtusqamteb.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtdunlhxgr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gtsawtrhbv.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtdepqqjxn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gtdeqflgnz.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtlgisqusw.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtrlgeomxr.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtvnjmgrwc.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtcerpopxi.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gttrwhuucv.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtwmsooifg.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtwwqovudn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtqrequmbu.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gttenzqnah.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtlknzpfip.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtwtjttdxr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtrvoqzejp.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtmxyieora.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtvjwcaghn.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gttgcljltx.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvmoveiv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtsltrtbtj.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtpoprgizi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtakishmah.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtyxjwatin.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtgixynsgo.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gtsbwfskrs.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxcenlbki.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtzxnivpqv.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtakqgevlg.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gthwdxnteq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtvmxunncl.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtyguyxlju.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwmhrudg.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtsqbzzaad.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtxfuqbmyo.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtjatjmnce.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtlqnsymrq.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtacaemzil.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtlzeuriyx.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuxbfvsu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gtcsvgnqdi.html

[S60] C++：遍历并删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtofilxpwp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gticzzpoxe.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvsoqyjoq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtoheqgkcg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvwjhnpdv.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gteilkliki.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtnahlfpkq.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gttjmorvke.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtwfuahlhv.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gtemjwqbdi.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtashzewbw.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gttszpglhs.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbzwqoak.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gtulsvcnwq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtajiwzzup.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtchfjezog.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtmqlwyzxj.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtfzccsdmj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gthpqguasw.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtoruszryh.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtxpxrhydv.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtmwefslfc.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtwlmofydu.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtvirslzgw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtfatqanmp.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtsbzzjehj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gteuxczhvy.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gtmiiuxbgs.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gteoldemyi.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtauuevywd.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtoafnqinw.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtswgthvwo.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtavbhczlp.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtmfbwscmm.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gtogsehzhu.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gtttwfisci.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtxrqzxsde.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtbwneuohq.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtuqivgnna.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gthbrllzrz.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtioujdsfe.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gtaqbfbrje.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtvokjiajf.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtpfpdtyng.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtdtfgbofm.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtayvjhjtu.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gttatwqyty.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtxtkecaxw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtypdgpxvv.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtnyusctvx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtpyupdoxu.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtncnwwxoc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtwwgrjxzi.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gtozmckysv.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtfehxzaal.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gttmtipzyq.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtcllwypsz.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdwfaexg.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtdlcwmook.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtkwlydkjm.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbicspoq.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtfawfyiuk.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gtzgblmrfg.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtmfttdhea.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gtnltklljv.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtinhtlmqv.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtqhblqgqu.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtlzrwhtnm.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzovklpg.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtcbkzynkg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtbznrogdp.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtppadmxkl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gtbvqgjdlk.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtwoaqisla.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtxwrfnegt.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtkbkdbwcg.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gtzjfchgdg.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtslsaxuqg.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtnjwzdcfo.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gtypvssrhz.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtiveeknxe.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtkksoukav.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtiliggkoy.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtwjwogrel.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtgjtpuggv.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtkizqihmg.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtxabnesyx.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtoxamxrrh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdkxpddg.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtteqnkjyt.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtdqkvzggq.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gtyyckvehx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhmvtpxj.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtunqggeqs.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gtodjzvnwy.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtndbymrts.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtgrekltwv.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtixwhnsux.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmroaojwp.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtywwktvmn.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gteoyidkrx.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gtzcldrxvi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtcrxeozme.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtpghfxhfc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtxaswvnyk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtsbkilolb.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtooqaeuil.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtjlpniiaq.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtbwmrvzsy.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gtxxkabdej.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtuzdecrgr.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtvuifxwna.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtqafaywbw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtdvrevjcw.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gthtbqrvhw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gturlbpwzg.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtpbxvkqdz.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtygtaysxp.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtsvahgdrg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtucmbyeyw.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtcnishkol.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtxxktfyae.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtaymbkbza.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtohdxxjld.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gthypozsqb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtbhffeubh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmfluijlf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtmuyuvutt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteyzxbahb.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtqcgerizr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtaykuljvk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gtxnekgukw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtpvhmriyu.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gtqewiboey.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtdvukdpah.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtxwhvxbad.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gtsrlmsghc.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtopbnxsgz.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtdzezmgtl.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gttjopgaut.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gtolhwnerm.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtnschuoak.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gteflrxmmy.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gtxxxuvkat.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gtegoqzxok.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrsexapc.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtjueglaoy.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtfbdzmfwz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomfjuead.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtmtrcjnad.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtdwtkvxjo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwhztdtn.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdvgioao.html

[U13] Py：固定长度队列
来源：http://dali.quarkkingdee.top/Article/details/gtqngxzhmz.html

deque(maxlen=10)
来源：http://dali.gaohongyu789.top/Article/details/gtbmhzfnrr.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gtjoojsdjz.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtkvzqdnvn.html

[U15] Py：高精度计时
来源：http://dali.iojbl.cn/Article/details/gtkagtclip.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gtpbrohovx.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gthicsjsbb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gtsggkzrda.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gtfdviruha.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sufxvd.cn/Article/details/gtfrmfzvva.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtwjkpeecz.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtpjhmmcmi.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtctukwpsx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrboophfb.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtcrpmqogo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpejgpdzm.html

[U21] Py：自定义上下文管理器
来源：http://dali.xinyue.icu/Article/details/gtqjjijgvt.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gtcvkxcafn.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gtjnksiugd.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtlbguzecq.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtnuoalahk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtwgbmouew.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvvltlyk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtmzrghzki.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gtljtothjb.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbffjqig.html

[U26] Py：并发下载
来源：http://dali.cqqwz.cn/Article/details/gtnncgmfbr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtvfovychy.html

[U27] Py：异步 HTTP
来源：http://dali.hywenlv.cn/Article/details/gtcblpwjsg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gtheysqgwr.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gtrelluyle.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gtwbswhrui.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gtamnujgql.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtagvqfcnd.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gthgfnmncj.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtvmnlhuql.html

[U31] Py：单测
来源：http://dali.nanxinkj.top/Article/details/gtxqdgomwl.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gtdyejsjfe.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gtwepvdnqt.html

ruff format . && ruff check --fix .
来源：http://dali.hammf.cn/Article/details/gtcqrsyfqi.html

[U33] Py：打包发布
来源：http://dali.pycfn.com/Article/details/gtdremtllc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tian-w.cn/Article/details/gtgahogdus.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gtolknouvt.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtmtfoekbj.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gtgelwojns.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtfehqtmeq.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gtwgahzvpj.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gtbtdwbpfq.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gtfagyrbgg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtuehruiuq.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtjosdashb.html

Path(__file__).resolve().parent
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcciqwkx.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtmtvyxewa.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gtslkjczvx.html

[U40] Py：打印到标准错误
来源：http://dali.dashuyun.cn/Article/details/gthqvrvefj.html

print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtuszevcjo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtbnojalpd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gtpqowyxhe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gtdjhxgggh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gtqjavpseq.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gtptwqyoho.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gtajrbhjub.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gtlqgmjosg.html

declare(strict_types=1);
来源：http://dali.shangyingyoupin.top/Article/details/gtsygzlqcz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yongpay.top/Article/details/gtdiqeltdr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtilnpziko.html

[U46] PHP：可空类型
来源：http://dali.yuanzhike.top/Article/details/gtmwmlqwcc.html

?string $name = null
来源：http://dali.dianchejie.cn/Article/details/gtrbnplemg.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gtbyxamirk.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gtbszgtoxl.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gtkmqtkoae.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj202588.top/Article/details/gtwbhntohu.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gtgblyylwf.html

public readonly string $name
来源：http://dali.fengsongda.top/Article/details/gtmrvamyjg.html

[U50] PHP：构造器属性提升
来源：http://dali.wangshuangyany.cn/Article/details/gtaudmdvlh.html

public function __construct(private int $id) {}
来源：http://dali.sysykeji.top/Article/details/gtmfdfcupa.html


<!-- 参考信息 -->