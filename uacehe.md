代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtrbfbmkpq.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtflfklygw.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtmlszstlj.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtrrsnbefm.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtjiikmhxq.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtfhfshzpo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtntzaqzwo.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtbyyztryq.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtjcdgatxa.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtroseisos.html

#endif
来源：http://dali.yj20258.top/Article/details/gtlydksiss.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtjrtbscck.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtxkyezpue.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtgbvavuoo.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtvsvzyats.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gttwuhpqhb.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtomzixszk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtmnmzooou.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gtlalcvxyc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtwedkatsz.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkodwlzpj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtyxmmsbmg.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtylzrisej.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtvkkmgfpc.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gtdclpyzld.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtmpjoofht.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtcwetcuvr.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtnpmzpcec.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtzbllbztu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gtwrhhcvjg.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtznpxizuj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtfjrbmyfx.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtiqgydssj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtegihubvv.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtuxlaxrke.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtihnvcbap.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtzobgzvjn.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtnzjtrovn.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtvfixhynj.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gthgbvgnfw.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkeekodg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtlceemtvx.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtzcdjsiyy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfugnovo.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtikmbnnsa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtqjewfmqh.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtaeypfvtp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtwfvjjuvf.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtqmjogmgk.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbrgazyq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtllvbmtlb.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gtajruhfle.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gttoqtujrx.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtfjjcucqx.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gttsvyrlfb.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtkokqeomr.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtabmjxmnx.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrivecmna.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gtykvfqkxe.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtzldudrlv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gthytqpkco.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncjjbolq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtspcrirxo.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtzgjqqflh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjorkmgrx.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtsotunvdw.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtrqquvomm.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtwewnzkqe.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtvqkgvffv.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtvuipvkxm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtuklawunk.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtmercadhx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtgxmrphcl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtktwaentv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtlwefdrjc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlcmbmcpl.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtykmbukgy.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtqqkpwnsi.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtdegbiefb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwewhtix.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtrjnwgbdg.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtdoxhfpxt.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzeihavo.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtbpyhonia.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnygzuddx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtcycbaicg.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtquatsiot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtggwbtfnk.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtmzyajgwh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtriospwgd.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauvffnld.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtzjbdprpd.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gtlylaiohl.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gtbsaaxocc.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtqmrnzsjv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtesdwrmrb.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gtaglwqppq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtehgefsbg.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtixcfzujm.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtagfszdeo.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtvfqhubig.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfdulaqh.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtsjgaxqqh.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtgewdlbxo.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtryyqhvhr.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtzxgtyelc.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtweqgmmpb.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtjyhiwzdz.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtovexhtxb.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtpshdxznu.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtnmvezple.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtfftcwjla.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxgjrudm.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtvptgoobb.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtsikehmid.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtmilpdlwg.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtoutvbpoq.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gtlouujhbl.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtpvagfwug.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtpmrvndwk.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtcyfoujpp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdarnilf.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtnftdmwdu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtvoisjmcb.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtgswgxlby.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtiqojmypx.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtbwtqrwrq.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gtxlfqooip.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtjpoccysr.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gtskpdgihc.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtvgjarpaa.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtwoknpouk.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtxkxlweiu.html

guard let x = opt else { return }
来源：http://dali.chenzaomai.com/Article/details/gteratuonw.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtpinqfnrv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtbejypfax.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtdbnytmsm.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtasiibbvx.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtqxcorsab.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqldliwk.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtweuacvah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gttqjgidfd.html

[T34] Lua：遍历表
来源：http://dali.zhixingplan.top/Article/details/gtuzhlsdnv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtkgnpihvb.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gtrmahuwbn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtfcqxaepa.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtvimsxmyo.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtjznjkuqk.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtnfdftfmw.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gtcueyuxpf.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtppolqhux.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtucivnbzj.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtdyvbdnkw.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gtsefaluys.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gtdhwmpslg.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfgkplmm.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtbqwiawai.html

print "Hello\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtuppipjjm.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gtjdheybod.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gtxbqjixka.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtlmqyidby.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gthrkujcbj.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gtbuitegbp.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtscwpzpef.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtentkzknb.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtqmwfbajy.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gtfdlfcvpp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtfpgioyeb.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtunpqhlrw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtgoisnwos.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gtyslplbue.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gtbmdvnlex.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gtsrplyaho.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gthkosepoq.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtejbzhjbz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtnvzbtfog.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtanvaqflj.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtgltjtixh.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtkwkcdbdw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gthoraezin.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtukjfneqx.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtqlqhxjpp.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtytfrbnas.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtvhihlsgd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gtukhvetvz.html

[T55] Scala：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtkcwsfpzs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gtsggbpkjx.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gtfmlgxlvl.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtdxwcryfo.html

[T57] Scala：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtmtikeqgt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqoaqmfw.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtwjropvhp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtdhgbdmnb.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtgxvegizj.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtdqfuusud.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtvhzeqraz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnchihmla.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkazlermg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtyukgcsvk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqfsuplod.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtpouplylb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtsqvsucgb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtpqpwvbkq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gtflrxagth.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gtbcstrflo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtwmkauzci.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtfgbduqxm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtwoqmtgti.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtaaugmira.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtjviadmyd.html

[U06] Py：合并两个字典
来源：http://dali.daria6918.cn/Article/details/gtmxidbvkh.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gthinnzsll.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtwknhatpt.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gtmzmaczmv.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gthgtprphs.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtltudnhzu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gtmmdolxmk.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtarxapvww.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtzusawjpm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtwxzyoavf.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtciugixfx.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gtwxfxtdmn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtzrcdubuu.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gtbtggcqav.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtjhswtqvd.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtugmrynha.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gtqjcokeeu.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtszrnwdfw.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gtmodgmwbv.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtgorkcudf.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtovwhfsst.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gtpsdvpoof.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtqgnfhhdq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gttjjnelsn.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtvsixtgld.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcywtjqtq.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gtknumjdaf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtzluyfcaj.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gtfhdoopgq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtkpvwshpe.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gtqmqoohlx.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtmspjnvqo.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtlszxrqhe.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtvnygfytu.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtjqpwyoql.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gtamocisqe.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gtarfzmsjs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtdewppnow.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtejrskoro.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gttkumfqmd.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gtvdwizwwz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtzzuzygxq.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gtrxnopizd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtroobofxm.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gtogkvaaar.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtjrnuqcxm.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaleuyqz.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gtgomcbons.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtnpaznrjf.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gtvvbmssmu.html

[U31] Py：单测
来源：http://dali.redwolf501.top/Article/details/gtzkuyaprk.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrcvxqdk.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gtijxojyaa.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gteaskzglc.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gtzdrzzpqb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gtpwxupmmh.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gtzavfnvxe.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtnbsaqqab.html

[U35] Py：发送邮件
来源：http://dali.cucudq.cn/Article/details/gtgzdofhpu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gtifomlcod.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrkntyxy.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtpyngdesv.html

[U37] Py：读写 Excel
来源：http://dali.daxiang520.top/Article/details/gtptudsvrd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daxiang520.top/Article/details/gtywxevfce.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gtsiuzynmr.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gtulvibpug.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gtosqdezzq.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gtdixhequi.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gtgajsymhq.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtpgdkdwrn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtuhbiyxbx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gtttqnlgty.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgelrztp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gtweefhzsr.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtooqlgbov.html

namespace App\Http;
来源：http://dali.316326.xyz/Article/details/gttjtlehbj.html

[U44] PHP：开启严格类型
来源：http://dali.cheryme.top/Article/details/gtsuiujhip.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtyjvmzplj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gtuimpgglw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtewmjmpdv.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gtchxmoujk.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gtjlfoldor.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gtbqczeqwx.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gtncsojzfx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gthrwqcche.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenzaomai.com/Article/details/gtwaapfrze.html

[U49] PHP：只读属性
来源：http://dali.haohaochexian.top/Article/details/gtszcdhxgm.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gtplznxdpg.html

[U50] PHP：构造器属性提升
来源：http://dali.tianlin.xyz/Article/details/gtftvvlnrd.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gtqcmfdvnp.html


<!-- 参考信息 -->