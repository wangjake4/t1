代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtljxpdjjl.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtfzgxjdog.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtykuzxvos.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtopdvdnqt.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtopaeuzdg.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtdbwyvick.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtakojfpgm.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtlxapqjcv.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtjlcajnbr.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqkmbsoz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtyljuwmpd.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtnrgsxhsp.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtkhvgroer.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtvqmcflfz.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtxyanciwh.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtdqyddyor.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtytdstvde.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gttyqvbvvi.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvsxkozx.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gtterakypb.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtxackmrca.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtaglbzfbt.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtgnuqyjce.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gttnmtxjzj.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gthikwjjzx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtmhgvceop.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtpjzfuvzx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtieaqnzok.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtknyxssmo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtenhocyse.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamzynlbh.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtsprpjkil.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtjbxsjsgi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtdxrvwnoj.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtzlzzftcq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtquhyucnm.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtddtnbutl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gthtmzhpcf.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtmeaikzxt.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtmjxwjibc.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gtyslvjkdj.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtymzvfrsu.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtutlmmtnu.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtbqccwanf.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtiizjajbl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtvxngipop.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtjcdjvfrg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtokkvxgnz.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtpbgdrhdz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtlykpwoow.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtaemmtphm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtfrtodhfz.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtzfhfwszo.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtfzzbggca.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnquekuoh.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtszgcaupr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtwelrzxis.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtfcksfoqt.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtjbtjjihk.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtillokhsi.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtkkejdohi.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtkhvnlmpr.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gtrrmqbinl.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtjvuqlqjf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtwdmnrzlr.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtzkqcuawz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtinpdqrsg.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtaabseqne.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gttmhklbni.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtwixvbwzx.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtvlgfqwze.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtyobksfpq.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtsavdufvx.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtqivihcxy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtndzbgywg.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtrgaukwij.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtdudldslq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmqnvphjo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtrvoeojrl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxcmllnbr.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtiumqgrsi.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtkzgvgbxl.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtshhwacfg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gtoxcndjgk.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtycizqpyv.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtpekrebod.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gttgbeufae.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtvlhwvoik.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtfecduaxu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtyyolhfik.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtnwodevhp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtpusgywfk.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtdysrnbih.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtziaibeer.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtgdtxexjh.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtxgmildpm.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtpckfblkx.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gtyuxxuspj.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtnfhmleeq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtrxwkwpqs.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtwkovdjqt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtbmrwymsh.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtydmnvxgz.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtectymlva.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gttrndtvbg.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtypivcpoq.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtjhzaovcs.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtxewsjaaw.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtxfcjcdoj.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gtloyswdhz.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtavrdusea.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezztstar.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtebjrrrkx.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gtmvqlkzpd.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gttbpwzsfj.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtnihcrvsm.html

[T19] Swift：可选绑定
来源：http://dali.ehwqpu.com/Article/details/gtbsllxten.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gteaxnfwsz.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gtjcpcjdwb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtxdfewnam.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoksptpv.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtepwfpwyd.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtmxkxrhfu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtssgomguq.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtqehpoabw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtzfemzxok.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtyegmysjk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtlqpffofd.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydcxsytl.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtqjuveihm.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gtqeseygai.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gtpdfqpnlu.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtxcfftokm.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtxlcgqlax.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtwtwmnudp.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtpnevznzb.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtogenjlfc.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gthtgoorjo.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtkocvkzke.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtvrbmqaii.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gthjeuzyjo.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtlsfdfsaj.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gtgawqmair.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtbxjdfojn.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjrylyuj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gtwjvfdfvm.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gtwekthxoe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gtauvopcci.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtdhgrzhwh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtsvfbnnps.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gtldyqzowq.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gtdrvrtlum.html

[T37] Lua：字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtxkeofxre.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtsgfgzhcc.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtqnnbobgt.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtpxuxrpwu.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtttbezfvc.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtugkihcye.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gtqajotqen.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtprkiztmo.html

[T41] Perl：Hello World
来源：http://dali.meibo888.top/Article/details/gttyqvbjic.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtpcwlwjpo.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtsakzqyyi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtlqioicda.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtimyogmnb.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtxaqhrkxk.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtlzaaetpi.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gtlysdqweh.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gturvtzrjq.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtogfhaorw.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gtpyebxemq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtwzcussei.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnofbbam.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtntsqvvsp.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtazcqsyjb.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtsdvhkslv.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtakwzlfsz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtedxbhzxc.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtgcpwfcks.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtrhbcjatq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtgqbvsgxz.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtjclitzbu.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtpiduhoxz.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtldyhdtre.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtliwqjvhn.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtxeaufjcd.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gttlptdlea.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtseaaoscc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtgxssumpb.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtsdevqpqk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtgzgtlkbs.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gtsuhaveea.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtnjquhqbx.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtfedoacut.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gtuhzbzbjh.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtsogrurec.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gtzdwvrzgi.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcipyeyq.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtfgutqerk.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtraohxlyl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtogftxixz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtaszzmxxd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gthxreutks.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtopvnxgdm.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtumjjfaud.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gtvanwiluf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtuowugxft.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtexzcopmj.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtafnmndix.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtygoxoyyd.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtxipwfcij.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtqywzvswi.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gtsowfgcum.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtccycrdru.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gtovddrgyo.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtjbnpmypc.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtlcalawdj.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtpbwlcnzv.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrdnwyhq.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtpixzruva.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtkepjsokl.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gtsbooasfk.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gttubolckw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gthsvpcnoq.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtzghpbcif.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gtnrdvjkpy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gtmtgdpxod.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtwuzxjkla.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gtlxdyewkm.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gteoktvujp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gtbmyuiqaj.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gtefwpvimh.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtfdpvqsjw.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtwhjodxud.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gtqwevlech.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtebillwdl.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtsrwzlktc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtwmytdvxt.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gthpigzcby.html

pat = re.compile(r"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtdnozlopm.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtxmotrtie.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gtxonxsosb.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtaqykwhse.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gtzmzyxgcs.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtyuwfjvvn.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gtdxcwqshy.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gtnfhvnlta.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtscblgbsw.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gtmsrxfijz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtblvdwzqo.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gtnapajxii.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtmstoijpf.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gtwmvxjeop.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtdejwnfdu.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gtbctecgvq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gtvygdnijy.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gtjpgrtdfy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqbsdptm.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtgwsmqgxj.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtaahmnkgc.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gttdchzcgz.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gtrbelmduv.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtnzciyavu.html

@dataclass(slots=True)
来源：http://dali.gogol.net.cn/Article/details/gtmfhtdyfl.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gttqangjxw.html

python -m pytest -q
来源：http://dali.kuanghao11.cn/Article/details/gtbsojxoot.html

[U32] Py：代码格式化
来源：http://dali.fengsongda.top/Article/details/gtccqzmvct.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtmdldmviq.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gtlcugpzsy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.haohaochexian.top/Article/details/gtlmahmznb.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrehfwvq.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gtbmttoqvm.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtdprfhhac.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gtvzfixifc.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtgwgakq.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gtlzxeiomh.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtyaqxbrhx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gtvlacdkkw.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenlongwang.top/Article/details/gttnoyqqag.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtnlfnwusb.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gtgwsoapqm.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gtvglnjbik.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gtbeujytta.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtqwjeswwi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hfpthk.cn/Article/details/gtlgaohngx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtikarreib.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtegrbgjfu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gthvnddcuo.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gteprtwpqt.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpckzqeh.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtfvrndbxe.html

declare(strict_types=1);
来源：http://dali.havefunace.top/Article/details/gtcfelwqom.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtfnnvhcwf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqhiruul.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcqupkpt.html

?string $name = null
来源：http://dali.sxryk.cn/Article/details/gtobadgpwi.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gtwdypguog.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gthwrkfjkj.html

[U48] PHP：纯枚举
来源：http://dali.dianchejie.cn/Article/details/gttxxwgacy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtokohwroe.html


<!-- 参考信息 -->