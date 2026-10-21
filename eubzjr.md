代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtfomnnycz.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtuxjztwhk.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtodluiwfp.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtkscpfkgx.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtbwoggrlw.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtlstucpvq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkeuqazu.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gtvwvipwtl.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtzaxbppgl.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtuhwihkxc.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtbyqmumau.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtvwdhfbnl.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtbcjqgpsk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtusjshhve.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtauhcvxbq.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtidfewlpp.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtnoelqxrd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtathtjbyh.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gttamhshhv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtlojljuzp.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtpokuhhyn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtdtpbxjzm.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gtxfkhkglq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtqqfkipyl.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gttaunmimw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtiquklpbh.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtybokdphh.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtxlyhdear.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtfvmiypmh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gtjmjqinii.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtiomwrdsd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtzzvryvus.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtyeishjrt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtpqvbkgeb.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gtfevtkgfc.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtldaofvdo.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtiqvfnhkz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtgudlcbhp.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gteiajqcxm.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gtvsqralyr.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshadfzjl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtgfcogrji.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtnrbmuntd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtkzpgwfxq.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtrbooxjah.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtsxpegija.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtemttolie.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtmtkzbjwg.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtxiwaiueh.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtnepxyglp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gtjxxelbkk.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtuhofjnwe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtkqyvwmeo.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtacbyhzbo.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtqqselgna.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gthtgewlkb.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtivekerar.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtnacyhesm.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtjpkyxvsl.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtsezwfvtt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtmqrvusew.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtuqtpdexz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtfmxaoavb.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtidrlrgdf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gtqqfoplct.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtxzojxzzq.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtjsbpparv.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtuqikyfbv.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gtfsebufqk.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtpwfxbwcj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtshilrftb.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtfczefhdp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtqvnkzjgq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthebtkllx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtmuztjsdp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlbhzbcay.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtxddvqtrq.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtfwnexonr.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtqerxxdxn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtycdrxybc.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtovczunwe.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gthvlksgtu.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtucyuuhzx.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwdldzfz.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtslkbyunm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtiuisdotz.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtqjypecej.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtwkdqoion.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtvwfqudai.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtjfeykxdi.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtandrhcaw.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtivwgscif.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtgdjhiorb.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtpmcaxvwi.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gttrjgfird.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gtqzsotcvq.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtexxiipod.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtqywxgise.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtczbsmwqw.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtjacyiwod.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtoipvtapp.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtmbukyosr.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtnrntsuxg.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtywsxqjxn.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gtsnanwcrf.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtibuseadq.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtfrpowfxa.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtaoacjzsq.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtscwsczoc.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtcxsepgcj.html

[T18] Swift：字符串插值
来源：http://dali.tanke756.top/Article/details/gtwapicaed.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtpmdbcivm.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtqewcsywn.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtcaawowaa.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtpbjbhwla.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtbaoyftvo.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtahzaofis.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtwziogbst.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtqlrpgcmx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtikfrpenb.html

[T23] Swift：函数
来源：http://dali.jqgfzy.top/Article/details/gtaibcehxu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtapbhpjcc.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gttvldmeff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtjqfdpnyu.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtgiwaaq.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gtocmiojhs.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gtpudlchtk.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gtfjhgnkmp.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtpsdyresj.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtahofolbd.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gtlglckrfk.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtpxzbkfaz.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gtexbilcmk.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtihpqityl.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtivbfrnmr.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtcghlhxdt.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gttuannsdf.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gttoqflmkr.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtwtunoncy.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtcxjwfkji.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtuqmhkhom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsqlujyq.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtglecqdjf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtnziuocdi.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtsmxpuzqc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gtljsuwvya.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtqyukwjlt.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtomvdfdud.html

[T37] Lua：字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtaoqkathh.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtzgpakhbd.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtioycgpqo.html

if x > 0 then print("正") end
来源：http://dali.yuxming.cn/Article/details/gtawdlqxxg.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtjjkmkkam.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtthmtivir.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtjlkicwbx.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gtgsvgsklr.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtlaxikxij.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtqoggsxqj.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtkjxentch.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkkjqoee.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtrmbdidcu.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gtapfabylx.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gthmmjfdwp.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfdivqpvc.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtgxjcagxp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gtseyadmll.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtbkxmyoyr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtdfefffbe.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtssyklnhh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtixogdbtk.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhewjklx.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtqpahixte.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtjblxprfn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtyugcgqkm.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtdmleqwrv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gtsazothsc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtonvbsfjv.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gteolftzid.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtefehfenf.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gtbozjrquj.html

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gtqlrozddp.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtwtlwrwib.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtlidsbqbh.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtisfoydqa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtmbskrxcd.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtdxsvjeid.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtminrmdgk.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gtjgyioeza.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gttdrikjba.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtjbjrykjr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gtimhpnvrj.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtfccraiag.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gtjfaejvit.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtnghnzfcw.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtvqauxiar.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gttejeoomz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gtlngwsnjk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkiuzkglb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtklqnilbc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrldvkyoh.html

[U01] Py：创建虚拟环境
来源：http://dali.gaohongyu789.top/Article/details/gtzeoqnxrg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gttvvnmjvi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtnsfevwis.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gtashfpjud.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtcxerttcy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gtaxvmfbmt.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gtoxiektwu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gtsemvpbof.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtuyqbziez.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtpyaltzzk.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypblbcoq.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtxmgrdvxc.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gtzpwhsddi.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gttdecsghj.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtfsopjtty.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gtyidynzva.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gtuawvjmbc.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzcapome.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizrjpmds.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtipxdxiyr.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtfylfbivs.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtpaabvywu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gtwyjfpzsz.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gtfjutdgqm.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gtwcsvdahb.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gtvgbyaxam.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gtijuhlxbn.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtbngcblon.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtiilvjkwq.html

t = time.perf_counter()
来源：http://dali.quarkkingdee.top/Article/details/gthcmxluxi.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gthwxklexc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gterlqadje.html

[U17] Py：初始化日志
来源：http://dali.yj20258.top/Article/details/gtwlteziuo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtuvqdduml.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwqdovja.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gtgkmwbkfm.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtttfzmsym.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnowvakas.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtwzmphyvv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gttmkkwdeq.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuanzx.com/Article/details/gtdbvtjubq.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtqmougxtd.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gtlovkfbko.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtukyybhbx.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gtbwgfvbut.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtowhlrack.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gtucmovjpl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtmlqdqkrz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtatvrmiss.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gtobfdpuzp.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gtuopktvzn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtbvdctair.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtdrwmwbfu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gtieqhgweh.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtasefddqg.html

UserId = int
来源：http://dali.hammf.cn/Article/details/gtqinlefda.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gtlhscfsks.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gthxtilgbs.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtktimaufu.html

@dataclass(slots=True)
来源：http://dali.tianlin.xyz/Article/details/gtgqvpyhjp.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtvqjhmyqb.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gtaxendjsv.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gtyyazmwfc.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gtjuoemood.html

[U33] Py：打包发布
来源：http://dali.quarkkingdee.top/Article/details/gtqourwvxc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.feifeiyinyue.top/Article/details/gtwpaidfkf.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gtxyyqwskq.html

chardet.detect(raw)
来源：http://dali.316326.xyz/Article/details/gtdkcgrrfg.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gtordjdkjl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gtyghninvc.html

[U36] Py：定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtetzieojq.html

schedule.every(10).minutes.do(job)
来源：http://dali.bjfxy.top/Article/details/gtzlsdooin.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtwofdmjfc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gtifxnxcqv.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekggebgj.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gttecgkgba.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtyhmrbnla.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqtupahz.html

[U40] Py：打印到标准错误
来源：http://dali.hysaishi.cn/Article/details/gtrmmhlhzv.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtolwpvlkb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gtzaxuyjld.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nwbrower.top/Article/details/gtvtshksiw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gtglgbtfeu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnedbegpz.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtjdsonaqm.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gtaahujuwq.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gttxgxmyts.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gtievcdymf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hongshengwenyu.top/Article/details/gtsqfygomh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtqykyatan.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gtexaruxxj.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gtyvneenms.html

[U47] PHP：联合类型
来源：http://dali.gaohongyu789.top/Article/details/gtunlbfnpy.html

int|string $id
来源：http://dali.cashguo.top/Article/details/gtxfundsek.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gtadxucusc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gtuvpzejpg.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtggcqtxym.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gtdlqjevdz.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gtgztliihy.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gtgyepthbq.html


<!-- 参考信息 -->