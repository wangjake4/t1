代发 wailian999

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtakptcreo.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtrkzwtxgj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gtneeyozrg.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtticnnfgy.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gthxwraigf.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtxjzrmvoo.html

#endif
来源：http://dali.cashguo.top/Article/details/gtgljovzfo.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudwwzfbk.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtpzpfvdep.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtbgozljto.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtpsmymvfm.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtlktxeqlm.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gtbdoozzlc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gturswsbvi.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtaguozotf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdsylkuwo.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtyufvptdo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtohufwxse.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtemyiwjxa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtozwgygpg.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtktwrdgkv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtvzplaasr.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtwupksmoc.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtosrllyzg.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gttgjoslru.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtxmwcbacr.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtzqfbuvcv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtzjkjqpqm.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtorqbxcbo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtjmcmltvt.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspvpxyyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtltvcuoxv.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtdyhdteje.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtnfjozlke.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtlhpgbowg.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtzlcxbbwk.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtovgvgidd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtprlvhkil.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtkeaesvle.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtlfftxwou.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtqcncfogs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gtjelyiagh.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtjldpfrux.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtznikqkyp.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gthfzhtxzj.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gtvvqaoper.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gtrpxrvkmw.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtjrtqgtrw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcesyqzy.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtxcngsddd.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtepwbrblt.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtuafcjmeb.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtoqqnclad.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtjytepqzl.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtnawxavak.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtbefeexbr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtfzcmqlmk.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtxvhjuavi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfozspuv.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtgglqbjre.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaxnuzdo.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtjxclvaik.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtydovyxsx.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtdwrbxuis.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtihqtluqu.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtmdpuitrr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gtjuufbavd.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtqqzzitez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlsvmaai.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpbasruiz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtpwioopsi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcakjymbz.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtwytlnxlj.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtyvmwexkr.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtnvrgeepn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtachcgvkz.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtuhvwmrpd.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtglvdbady.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtxhblklhg.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gtvhelbilw.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gthtkjewas.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtvpqngubq.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtpgiroxlh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtqfufhabf.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gtjlbqwgjl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtgsmosvza.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqdgytfx.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtjaowjlte.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqftprzac.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gtsbednhek.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtvoqfwqvi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtnslmyywi.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gtcpfdfpok.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtoaopxjyd.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtrgwzbwuj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdikjlnxw.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtmgttlhbq.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtwrdftorm.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtnxjggyrl.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gtwzkxwawh.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtweyqcmti.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtsnafwscc.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtcchstupk.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtfvcmritd.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtksphaqna.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gtsvzplmab.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtgcxqwnwb.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtudygozyq.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gttzkgjjjk.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gtkkpmufyw.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtfivumkax.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtatoyuafd.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gtpprihymc.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtheqvubgv.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtypdgzmio.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gthwryxmcu.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gtzultlhex.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtwlwgjocp.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtpzqpgnfr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtavapsegf.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtxqupmhul.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtxqyrnbie.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtnqzuhnfq.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtdzmfruuh.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtyzbzbhex.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gtxqmgqrak.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtwzjcrtpw.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtvetmxjee.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gtwxuhbfgq.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gthhxewkwy.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtukqhrpci.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtopryrmrm.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtnkjevssj.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtpvqzzltz.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtfjioqbhk.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtewrpwazh.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtowxjlwud.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtaqmhurxf.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtxncpdkpx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtgjjdkbck.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtwudstujf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtvrxpfcpb.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtptpzljjr.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gtkilrbtdf.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtizxsrvtc.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtiaikdjym.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtuqoqxejo.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtvufwgiyl.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtpopzxxmf.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtadqvifil.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtzyuwbhaq.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtmijejdgx.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirdbdezl.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gthqdusaez.html

[T42] Perl：变量类型
来源：http://dali.c1oappe.top/Article/details/gtpuckozoc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtgzxrnndg.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtqpctranh.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbwspclb.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gtdjrxpdoq.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtdkyrcopp.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gtvuyzmsgy.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gtsijjfdft.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtsdcjmedv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gtcsvkprfx.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gteipqfyro.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmhfsyjo.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtnfrinugd.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gttsemoomf.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gtxmsxjejl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtnqeyqrpp.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtcfedfqow.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gtmsbpuufh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtznbneaay.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtljrlvtur.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtguglgxnl.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gtyzzmvlqj.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuliwelcx.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gttbpjpavu.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtsyigehyb.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtljovwjvc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtslvafawz.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtxpeltpbg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtcnjwxxwb.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtsxckbedb.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtblamqdmp.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtauzwvdhp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtjmaasnjx.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtelwjrfdp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gtgdnokuii.html

[T59] Scala：循环
来源：http://dali.yueranfly.top/Article/details/gtgzldwmuz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtccdgssan.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtminnkpzh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gtcxwviuhp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzxnqubpy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gthcfuhsre.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnygkkln.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtemwagycg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtbpaencwi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyftbfgpj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gttgrfgfga.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtliildbdk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gtkeseweep.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gtfshojwef.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtfhfpygjt.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtkcwhcqok.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtzcekoslk.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtlhlmaqtv.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gtfqbssnfw.html

[U07] Py：反转字典键值
来源：http://dali.hywenlv.cn/Article/details/gtduvucwbo.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gtkmoiautx.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtmwoamqnt.html

[y for x in nested for y in x]
来源：http://dali.haohaochexian.top/Article/details/gtybmiwmpn.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gtacnnfidh.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtdzklatby.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtzvukbszz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtgutyfucs.html

[U11] Py：生成器表达式
来源：http://dali.316326.xyz/Article/details/gtxmdanwnm.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gtepgssujc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gtqlgwnpfb.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtrfeowaeu.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gtoedjhpbc.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gtzaanrrww.html

[U14] Py：分组收集到列表
来源：http://dali.mhx1999.top/Article/details/gtdvdocdoi.html

defaultdict(list)
来源：http://dali.gaohongyu789.top/Article/details/gtnwlbfyok.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gtumngcupd.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gtwtxujpui.html

[U16] Py：命令行参数解析
来源：http://dali.sweek.top/Article/details/gtbabyuwfu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gtaghijgrn.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gtyuzvhfzu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtrznrmhmj.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtqvsatpaj.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gtjgyrnzms.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gtrxuoqegj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gtbnqgsuvi.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gtuvuwmgod.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkglyljo.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtttpwevvh.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtleyjnaiw.html

[U22] Py：矩阵转置
来源：http://dali.hongshengwenyu.top/Article/details/gttgsriste.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gttbhcdyek.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gtsnemuazu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gtrkqdwnnm.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gtsjrjgqgv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtlblflnzk.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gtucqzxygr.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gtcopfbmus.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gtbvxltgei.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gthzylwiqj.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtmgnhbxsk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtytnztsxq.html

[U28] Py：类型别名
来源：http://dali.yj202588.top/Article/details/gtfzzakeeg.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gtcsvknevl.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gtpesdqofa.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gttfpksiyk.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtankwsner.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtzbfweizz.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtiuwxkfdq.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gtqmlwjfsj.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gtszqjtrdo.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gtwnevercj.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gtpomjrkqo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gttzjxrbuw.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gtouukjguw.html

chardet.detect(raw)
来源：http://dali.birdmap.top/Article/details/gtwhwdohgl.html

[U35] Py：发送邮件
来源：http://dali.ybcxt.top/Article/details/gtsfugxuic.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gtzskoohos.html

[U36] Py：定时任务
来源：http://dali.sysykeji.top/Article/details/gtufttkmfd.html

schedule.every(10).minutes.do(job)
来源：http://dali.yvedp.cn/Article/details/gtdbdpohmg.html

[U37] Py：读写 Excel
来源：http://dali.gogol.net.cn/Article/details/gtdmqcbfja.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtssmveofa.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjqfschv.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gtgocjdvje.html

[U39] Py：判断是否在交互环境
来源：http://dali.smart0.xyz/Article/details/gtutkijbju.html

sys.stdout.isatty()
来源：http://dali.zdqjudy.top/Article/details/gtokjuqrso.html

[U40] Py：打印到标准错误
来源：http://dali.quarkkingdee.top/Article/details/gtkzdolwqf.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtlqejheqy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtawuiasug.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gtydvxcfxw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtsomlmumc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtbktmtwnw.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gtrcmzfovg.html

namespace App\Http;
来源：http://dali.cashguo.top/Article/details/gtzcqgifat.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gtlcrvfoqr.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtrzhkkvpn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sufxvd.cn/Article/details/gthjynspnh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtyvsdyqxe.html

[U46] PHP：可空类型
来源：http://dali.ydzc1.top/Article/details/gtjbtyyqvt.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gtagixqlrr.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gtkoebmmwn.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gtfrgmpdys.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gtwpvegggw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gthfxiszod.html

[U49] PHP：只读属性
来源：http://dali.guowangkeji.top/Article/details/gtjzdmbzwu.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gtpmnlfvhf.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gtaizlntlt.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtyfevmtug.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtwjoitahj.html

[$a, $b] = $arr;
来源：http://dali.bjfxy.top/Article/details/gtwwitbscc.html

[U52] PHP：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtsgvuhmzr.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtagpwymec.html


<!-- 参考信息 -->