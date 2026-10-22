代发 wailian999

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtpgocpwcr.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtzvpnlfdj.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtlxrgkkng.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtjztyvgcm.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gtlukouihq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gteqkjnxrw.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtfbxundaj.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtrpodxhly.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtbyuugqhc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtpdxtdjdx.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtxnpollbp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtirdliucp.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtyjvhngsg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtiqtwvntn.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtuxsgsswe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtzymfifyv.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtkmlopwrm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtermbxoit.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gttslhjphc.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtemmjvgxp.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtfvfolqny.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtykxjbewb.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtpvhckddj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtjuoqnvmr.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtbluubsrc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtukbibwkk.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtguwgzlvm.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gtsswaitin.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtyndkpwbf.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsxdqwsc.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafwljwib.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtesxldahp.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtypwisqmn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtnrbaounb.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtxtwzzrrh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtioeeqogn.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtzxknqubd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dashuyun.cn/Article/details/gttfiatqic.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtkwpknrdo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtmqzkfhsz.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtxatkgnod.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtagfsvmmc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtlomqwmfd.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtxpjsrnxh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gteryifksq.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtkpusdnvw.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtstrvqikh.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtbhcsqeoa.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtfqbbdlqr.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqjlcgyl.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtgvhnxdte.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtotxzvixc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtrlgbaago.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtfjvtvuhw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtawuxiydi.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtgmjtkeih.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttufbxsl.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtwaqgfhqi.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtjajgpybz.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvaoenwm.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtosxlimzp.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gteyysslnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gtapnginlo.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtwzdbsvpf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtpovwakbd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmgpolumq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttwcxdes.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtktgweuny.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtnuvropcv.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtnadgtunf.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gttwgaztxg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtgmtvgymg.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtzeiwpycn.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtowyxnzzf.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtvoapjaru.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtounjtivg.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gtbzcojvij.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtkrlsklfw.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtygtcznnf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtxpdfeial.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtcsahicsy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtlefrfvni.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gttaclubdt.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtkuengmra.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtfjlyuccf.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtiujpabal.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtpzzjhqtr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gtwanwwzlo.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gthneaztnq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtuxojulis.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtptjgtbny.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtiuvlejyy.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtyuuxlerz.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtnxxlgkkt.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtcrnqvlsw.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtllgwrumr.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtklcsqgcx.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gtrgwtbeei.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtoefudufo.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtfakpwhlm.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtxnhhshnp.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtqyjccytf.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtmvcyuvug.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gteonorvsb.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzknypwds.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtgxxpangs.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gtnrgjlulz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtcwsankkf.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtsbmkgosu.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtwuaisjqg.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtqlusueof.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtvcoqgeoy.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtwqpmctzj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gtymeydobx.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gttvyijnfd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtpthafngv.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtgwekaxfw.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqgeszmx.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtezrbwhwl.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gthesvcojv.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtwchbawnw.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gtuklwicag.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtppljvleb.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtelxmmvvm.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtfmbqkcsy.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gtpkwtvexz.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtisijdxzx.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtfkjvtgxe.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtdwhvcovg.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtlglpduil.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtefrgggbe.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gtwtnclvqg.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtkhvkrksf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtkfxtdmyp.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gtegcuejyl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gthcbmxibf.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcjlnjxl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtnrmbrntk.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtlavvhhdo.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtvfbhqcab.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtxnybxwwm.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gtiwaujeek.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtnmqcjmxz.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtqtaqohak.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtjytmzkbo.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtqmgenbfj.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gttfntomqt.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtujymmchq.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gtpdqyiosm.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtvrsvebfo.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtngkuktmq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gtyhnjenaa.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtnvfmgasb.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtjsgxkecp.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gtmwruamdp.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtenkrpjhq.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtoyehnwyl.html

for my $x (@arr) { print $x; }
来源：http://dali.fengsongda.top/Article/details/gtuywvbhda.html

[T46] Perl：哈希操作
来源：http://dali.pycfn.com/Article/details/gtxnshefhz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gtspvaldph.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gtdcpnrykb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gtvmqshllk.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtskodwamj.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtvqiccoek.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtoclhncsv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtrynoqvnd.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqzyctkjf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gtsnnjyyqn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtvianztce.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtobzkwakk.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtmgrnjvrl.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtfllrourg.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gtdmxftibj.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtcagsxkro.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtuwlymbru.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gthzeauuha.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtsuanqaqa.html

[T55] Scala：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtqtknmxzm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gtcwckfqhm.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gtohylduxd.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gtbmgsuyfi.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnralxzb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtrgpfgmlx.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gteachupge.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtkdbtoczk.html

[T59] Scala：循环
来源：http://dali.meibo888.top/Article/details/gtxgfudcgv.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtcufskfet.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtwvvkozrx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gtnmzaxyel.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtklerydiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gturmqmams.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxszdnee.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtnesimtwf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtlnfndpsd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtvhwzvbkt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtbbncgazd.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtcdkuhtcn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhyiorrp.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtsgtumpnz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtebmwsrbe.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gtmhiqasza.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtujiivduy.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtaomimqkv.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtvytodnrv.html

[U07] Py：反转字典键值
来源：http://dali.yueranfly.top/Article/details/gtjkorjwyf.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gtqlgpwqre.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gtjwgtbfxd.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtffqiheok.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gtmzqynuqu.html

max(d, key=d.get)
来源：http://dali.tian-w.cn/Article/details/gtvyuwdosb.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcjtqynn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gtdclenyox.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtduzpvlxh.html

(x * 2 for x in arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtelscixhn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtvicvjapy.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtelcnphyl.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gtsjnvuiuw.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtdyevbyrk.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtdvtxfyzc.html

defaultdict(list)
来源：http://dali.havefunace.top/Article/details/gtugwwbkek.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gtlrrlaulj.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtjbisflxo.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtdxbdzhlt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gtsrtzfcqc.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtdaiczuxq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtumisgcxq.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gtrpezlbpt.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtwqlxgart.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gtqwntffot.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtmlyzfbzf.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdkzmtqv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gthixoknnn.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gthhnrmvfk.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtzcuoqfza.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtfxeiiggd.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtsvlpdnfp.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gtuqjzhcqv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtvdmctghz.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsjpqsne.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtiznzlbjj.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtuoglsiua.html

csv.DictReader(f)
来源：http://dali.zdqjudy.top/Article/details/gtfgoqmdsz.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gtojpizsnn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtutchkool.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gtcoayzbhy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gtzlgmfryi.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gtgjiiovol.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gtmgtnkkfs.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtfiyqhcgq.html

@property 与 @x.setter 配合
来源：http://dali.yuxming.cn/Article/details/gtobzwlwdf.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gttbnxnmxy.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtwpipsbza.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtcwbepxpr.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtfwlwsunw.html

[U32] Py：代码格式化
来源：http://dali.cdnleiting.top/Article/details/gtivorzlvd.html

ruff format . && ruff check --fix .
来源：http://dali.jianghu66.top/Article/details/gthowfbfhd.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gtegjbryst.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gtecykvcpd.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gtbdosyjjs.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthytuskte.html

[U35] Py：发送邮件
来源：http://dali.pengpengdd.cyou/Article/details/gtwkszrxql.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtcvwwsfie.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubnwuazs.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gtfjawjevf.html

[U37] Py：读写 Excel
来源：http://dali.cqqwz.cn/Article/details/gtdzbnsqfr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.andypj.xyz/Article/details/gttouitemo.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmmilvgx.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gtfgjhnoof.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258888.top/Article/details/gtqketnggy.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtnldgcyyv.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtyeadmcud.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtlvhrywow.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtucmlxqlt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtvoxkriab.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gtuogxcsol.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gtknpgdxtl.html

[U43] PHP：声明命名空间
来源：http://dali.ppjwa.cn/Article/details/gtmxtwrbix.html

namespace App\Http;
来源：http://dali.xylfe.cn/Article/details/gtczlrksyw.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gtltqedaai.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gtgjznkakq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gttgkkvlgd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtvxnyvmyt.html

[U46] PHP：可空类型
来源：http://dali.bjfxy.top/Article/details/gtftzudkzo.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtbrbkmyro.html

[U47] PHP：联合类型
来源：http://dali.bjfxy.top/Article/details/gtduvukjwd.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gtknztdobp.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gttvteorqx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gtloafsxvn.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gtwrfrafqh.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gtmrnugaar.html

[U50] PHP：构造器属性提升
来源：http://dali.gotoacloud.top/Article/details/gtthtlenru.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gtsaxsnswb.html

[U51] PHP：数组解构
来源：http://dali.feifeiyinyue.top/Article/details/gttafqznzy.html

[$a, $b] = $arr;
来源：http://dali.havefunace.top/Article/details/gtubxywoxi.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtokmumeuo.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtcopalptn.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gtzjjfafcy.html

$v = $a ?? $b ?? "default";
来源：http://dali.sufxvd.cn/Article/details/gtnvdpvwmi.html

[U54] PHP：空安全调用
来源：http://dali.guowangkeji.top/Article/details/gttrwtvqlg.html

$obj?->method()
来源：http://dali.xinyue.icu/Article/details/gtrhttabjd.html


<!-- 参考信息 -->