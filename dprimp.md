代发 wailian999

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtxydciqvp.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gtzzvonjcy.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtrvkwqmmn.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtnrgfssme.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtdpcdzvqp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvbkjpyc.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtcjwrzbvu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gttyaftegx.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtfvmaglpe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gtsywcibjq.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtojuklxgk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gttcdcywmo.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtwmxgurrk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtcidzscza.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtdodltamh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtnwtnzxlt.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtpvnxoyoj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtlhwrvhvs.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtpshlmwps.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtgofzdegi.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtolhbmrlj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gtrvuyizap.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtskwwppyr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gtuwjloijh.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtuybzipom.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtdvtbiqgk.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gtkucywigf.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gthzcbpcij.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtaemdlyfz.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gteynwqdqo.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtznmsnzus.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtdamarylz.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgocegbjx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gtxcazbnqc.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtulsygorl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtcbsucqmb.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtprqmqpvu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtnujwbtjg.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtberltbhu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtcwwuojdw.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtcxjklwrj.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtmhltbzxd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gtbpzerxtg.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtxsrmqzti.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtedyfghtt.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtuzzxwuht.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtwfykebah.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtpvjeasci.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtdbzwrhbu.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtfumnspux.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtwsfhvzfb.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtzrgqbzir.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtcqsbkwrt.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtztbithjr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtdhfpuegv.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gtrdnpoiwk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gteddcezyd.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtluabdenh.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtawqycjpe.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtiozcozaa.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtdyjalpsi.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtuchkbhrw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtbaxboklr.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gtnssmjtxz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywffhfqi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtukkzmskb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtbczhiopf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqitpsorv.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtubzsbyde.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtlvvpgmhk.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gtmvpxcnts.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtekcfnijl.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gthpyxrmso.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtzuvwslsh.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtzylralqc.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtbjmacfyk.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtoallwkhk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuxeuthd.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtvcfmczgb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtkexzzrvs.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtecmfihtq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gtvfacbbpt.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtlxnssnpe.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtvefwknia.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexeizymr.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gtqgiivgep.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gtmchfkguu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtmjfhjzmf.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gthlqgavqm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtkqetksxc.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gthhnqcwpr.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtyuphjivb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzvtvwww.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtsaxmrtos.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtxwvdxhup.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtcdfwstlj.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtsmzfmxha.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtrahzcucn.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gtfxwusjrk.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtfkqtuyzr.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtswwznlym.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtxvdyspnb.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtmgmwlzwm.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtnrdnesgw.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtbvdnmkzb.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gtytkzsfsw.html

[T20] Swift：数组操作
来源：http://dali.ehwqpu.com/Article/details/gtknarjojv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gtmqasznzu.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gtdhbltuao.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gttarppvcc.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtpmaoxkwc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuwfbhnj.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtynxlxnxo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtihlvqphp.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtteowjmks.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtyikmvquf.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtpiqnartj.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gtazsvcwdg.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtlmwlfuwx.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtnyrbqyrh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtwfzzqhqx.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtscxjurjf.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtixadcvbd.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtqoxawiuv.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaxabhag.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gteqdcgkaj.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gtmpvldiev.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtnraqljrn.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfjjzrii.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtbnckqwxm.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gtyzbfinad.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtgjemdlfe.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtextcpnti.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gthdvbjydj.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gticqqkrqy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtrtkjcabg.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtysxvnffh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtfcdqcyqt.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gthlpgezek.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gttefvlncy.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtxhpzdlua.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtcsynenmq.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gtkylnquaz.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtsvxjdppw.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtnstlavkr.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtflfusris.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtbfqnruiw.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtyigprdon.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtopacvzus.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gttqsrmqkf.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtthlfztjb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gtezqezrwf.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtgyjnhzbm.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtnsvpiuut.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtpirrcovb.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtpkghtdqr.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtadjeottq.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtocciwjud.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmprljwnm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtolclzvxw.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtvhdmtnnk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gtppraqlcx.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtmzvkwkjk.html

$s =~ s/old/new/g;
来源：http://dali.yonumen.top/Article/details/gtsmttoyzi.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtnubxqvtj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxfdmnbt.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtbwxfwkhn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtcqnmupcb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtnmtujmco.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtggcrbybl.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtbaynkfyl.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gtbuusykcm.html

val a = 1;  var b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtkjivhpio.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtsvhbowki.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtjhgaloph.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gtegqgaqiz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtttdhcyos.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtaidkgbxl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtdmopyzkm.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtsfxgreqh.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtkqeldvbb.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gtjckjtmzu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtlmpglgbe.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gtfthnvkrf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtdwxnzukk.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gtepmiaupc.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtsoawcrkg.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvbdhhvt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtlcxedbyz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdbvfipxp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtgpueygxn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdsxkaraz.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gtwlvwlvmg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gtffejylid.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtnexowzcc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gtwgqjxmzf.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtwicmdhad.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtrjzlhhkn.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gttyydsbrb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtmijlxvac.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtlkbjtinn.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtuppmtbhz.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtfqbuevmn.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtlsfjsqwn.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtnibmdybn.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtjfkjybne.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtpasafmdi.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtjupmhhah.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gtmtgbwccy.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gtxavzesua.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtkpydrz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gtfsouitzm.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gtbelqywyf.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtsyljcaes.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtwqmofmby.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtinbwisto.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gtsljnkddk.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtjsbmxzxu.html

[U14] Py：分组收集到列表
来源：http://dali.ybcxt.top/Article/details/gtdqravpmw.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtjlolofqk.html

[U15] Py：高精度计时
来源：http://dali.fzhhl.top/Article/details/gtzmmbgqrh.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtunvgzivm.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gtvbujdoap.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gtclorjkio.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gtxkoldukt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gtxvampzdf.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gtjpuxdfhj.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtnarohnuo.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gtegnyhpqv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqmauziw.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gtetddjxgu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gtgfedyhpf.html

[U21] Py：自定义上下文管理器
来源：http://dali.sweek.top/Article/details/gtvjmawopo.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gtfigmydsb.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtxwcwyqcv.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtehpjwtzq.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtufrlgssi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtrrzsdczy.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtkhanrfhq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtcsudofjq.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtqjmvnvro.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtlxspxogs.html

[U26] Py：并发下载
来源：http://dali.sweek.top/Article/details/gthgtockey.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtqmlhjawv.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtcbyyfbxv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gtaoqhvgqa.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtxznefszr.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gtbeeevjls.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrgsdhrk.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gtzhplphcq.html

[U30] Py：数据类
来源：http://dali.pycfn.com/Article/details/gtofcsbydh.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtyiylyqjd.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gtsybtmurq.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtbmbwwvwv.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gtwygdzqcj.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtufeuaacl.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwthltei.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtvebfutrw.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gtesqoxkpb.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gtbguubegs.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsplgsxj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gtpojdykvv.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsruwdgr.html

schedule.every(10).minutes.do(job)
来源：http://dali.yanxiufei.cn/Article/details/gtmwlrndux.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gtwrinjzog.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gtjwrkvrqo.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtmsooknyo.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gttjhbluhu.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gtbipcinsy.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gtyybpiwfu.html

[U40] Py：打印到标准错误
来源：http://dali.smart0.xyz/Article/details/gtkskcquly.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtzfcqjxto.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gtfnoahzph.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gtpucelghn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gtaiaflmpq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gtorrhlzvf.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gtqwamntdr.html

namespace App\Http;
来源：http://dali.nanxinkj.top/Article/details/gtbvwgwdrw.html

[U44] PHP：开启严格类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsganunbm.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtnqeeyxnw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aizwys.cn/Article/details/gteoatuczg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtvvrmacit.html

[U46] PHP：可空类型
来源：http://dali.chenlongwang.top/Article/details/gtdetvcziu.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtswxzxupm.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gtdksxwqlv.html

int|string $id
来源：http://dali.yonumen.top/Article/details/gtdrggukfl.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gtnyubhezi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gtjppnsvwe.html

[U49] PHP：只读属性
来源：http://dali.zhoulong.xyz/Article/details/gtndfihbli.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gthmhrjvyb.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gttutvftjf.html

public function __construct(private int $id) {}
来源：http://dali.nanxuanxn.top/Article/details/gtevwkmhpe.html

[U51] PHP：数组解构
来源：http://dali.cheryme.top/Article/details/gtabbgehhu.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gtksrdcqwh.html

[U52] PHP：箭头函数
来源：http://dali.cashguo.top/Article/details/gtxuhckvbh.html

$double = fn($x) => $x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtywompeuy.html

[U53] PHP：空合并运算符
来源：http://dali.guannengcc.top/Article/details/gtblnsexdm.html

$v = $a ?? $b ?? "default";
来源：http://dali.guannengcc.top/Article/details/gttaaikusa.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckxrnbhb.html

$obj?->method()
来源：http://dali.xylfe.cn/Article/details/gtirhlfidf.html


<!-- 参考信息 -->