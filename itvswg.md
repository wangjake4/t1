代发 wailian999

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtjayzdemk.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfpwvffo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtsozdtqvg.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gtkgdjwuht.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtsygvsrmg.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtnowstvqy.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtnlfudziz.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtzcedzkec.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtholqjrpz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtbiofteau.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtfdfglchj.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtlfnzbhgy.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtvnqvkegz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtczadcnbh.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtkjulieko.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtyviewnvt.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gtefkhuefi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtntivsfxn.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtvnvesqqp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpvhdzvg.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtlnmflwts.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtrqgypsnr.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtsaihvohs.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtixuxxpht.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvktvrmx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtnoigeiwr.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gttrbiixhe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtztlugjge.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtbxdbuxat.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtrdormwcv.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtsmsligkz.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gthibehzgz.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtbworxoou.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gteoqiglgj.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtnebdtuqi.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtfdqmeimq.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtwbkxmlip.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtpiifcvvk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtumfkhufo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtpephqqve.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtpdltiezr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtyksondwi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtzwqletpq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gtbppijzcg.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtmjbrrwqt.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtknqpjhcw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtlsqczrpn.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gtoyjjtdpf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtzhjxjyhy.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gttbshlixg.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtojdkukvp.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtetmtbfmq.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gthtmqgyuo.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gteefzunfc.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtirfccvrs.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gtwycgkgfa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtecatenqf.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtwdpxkecq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtehbchdfz.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtgczzmnab.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gthueiqavm.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtfaaznnng.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtgeecejnb.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gttovhndsp.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gtldjkails.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtmqgqsqmn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtsjtgioqd.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtjnqotaku.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtzxtjoyvz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gturwqjzkx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtvfsbpiak.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gticnegeas.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtdnalsqgq.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtzylwplvq.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtnstfqbpa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gteqdbukbt.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtnhkgxztv.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtznnzdarx.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtrhzhaqnr.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gthgtdmvzl.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtrpofsdsx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtozsrmkoe.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtfihmxpea.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gthjwybrki.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtvglcxcuj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gthvjnxegf.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtnbpothzm.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtdveokxnk.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtfypepgbj.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtvttehgnl.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtlvtoznyx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtbkbezjei.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtgxgfwmuc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtybegpcuy.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtzqzlcmag.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtjghzgdxy.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtvpwvnbdq.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtwsqykqir.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gtpsxrmufe.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtfzfmiqjp.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtomtqkbkr.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtfapaumit.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtbudtwzei.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtojqnycvi.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtyzadtjef.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtkuucstro.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtqhcnayju.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gtaliejfuv.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtkmrjowff.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gteysaglic.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtshdfegat.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtuuxkwhxx.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtnldqdxam.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gtrfeysggb.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtonueyiok.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gtoitxolfm.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gtiwxsuhqa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtvshgjnit.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gttkqknywv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtmrjdcxot.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gtrvswntcp.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtvcqrluik.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gttwrngpef.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtjmtjbbrr.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtvlbpaxyi.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtbxbbkhsx.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtylxcraxd.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gtopfjkjgk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykiglieg.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtkfnxdzkn.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtoftmhruj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttblmvkof.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtbozlxfvv.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtvyvcxcqh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtkpejajqv.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtmvhncnmk.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtdvbhpcrr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtuheqhbpl.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtzqvsxfqr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtthintgpt.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtlfdbbkyo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqclhptd.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtgxfhyefz.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtrmjrzeyk.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtardzgxre.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtjbhamkat.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gttstzburl.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gthlwfarpd.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtdzcjdikx.html

string.find(s, "%d+")
来源：http://dali.hfpthk.cn/Article/details/gtkiqodnfh.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtsjxcsxxc.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtqbgihozj.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuunacve.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtawbomxvf.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtemfxbvxs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gthtjlfhlq.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtpshjnffg.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtjzkflotm.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gthzlgmvfl.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gtqsszyeaw.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtlkmlwrln.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gtsyvrlygs.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtstvrtdoo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtiaqrdprl.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcolgciyn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gtfeyzrecl.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtolausiph.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gtesvqdeyc.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gtnpswfyia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtqqplpxxg.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtknygmpwt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gtfgnktjpy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gtaflvgczd.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtjognornp.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtixfvhrif.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gtiycsvozy.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtyzxmhcsa.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtqvmpmuhf.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtlaadbhje.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtvabvssau.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtzhdminxu.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtztarixbk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtsmjbvtxh.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtganqjvyw.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtxksoemio.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtnqyqptnm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtnwcdgras.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtczjcnvwj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gthzipgdnb.html

[T59] Scala：循环
来源：http://dali.chenzaomai.com/Article/details/gtwlwzydnr.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtizmfhhel.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtateinjbe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gtmykukdab.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtycaexzdl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtkeonuavx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbgweixvo.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gthycnlbed.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.svipenyu.cn/Article/details/gtjfubxazs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gtxfazkonc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpdvkqgb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtvruzyohx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtfgigscln.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtzcvvuqzm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gtwoaiirzp.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtadhnglig.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtjnjjirop.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtbdjctufq.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gtosfpxpeu.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtonnwkuot.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtalyouble.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gturybnunv.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gtwrespvhn.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtxqhyqasg.html

max(d, key=d.get)
来源：http://dali.shuidangran.top/Article/details/gtndpzabte.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtlvlxzulx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtwrfdoztt.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtfsupzggh.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gtnwdaynbb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gtkgdidppr.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gtvkxogwyj.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gtsbwnanwt.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gtbnpvujno.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gtsjirealc.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdutmwbn.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtjjghenoc.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gtnfboyomf.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gtublkenib.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gtbpltjsnl.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gtwovyghyb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gthyigqmgh.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtcogwpliq.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtsfehalui.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gtorjzhltm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gtksyqvbiq.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtsecjehqz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtrdhzfnbe.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtdbgliimf.html

@contextlib.contextmanager
来源：http://dali.zhoulong.xyz/Article/details/gtqemfeeni.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtoimrgwub.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gtrcidwsxz.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gtpuodroky.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.smart0.xyz/Article/details/gtplbtkqlt.html

[U24] Py：路径操作
来源：http://dali.daria6918.cn/Article/details/gttvdgztub.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtsbagsywf.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqrpvwcv.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gtqswpfnkf.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gthcqljqzi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhongyouzk.top/Article/details/gtzukjhlxf.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtsxzyqwkg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gtsiofbjbl.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gtqcsteudu.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtkqarswge.html

[U29] Py：属性校验
来源：http://dali.zhoulong.xyz/Article/details/gttkhrrqex.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gtdqvhgplm.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtrywoiddw.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gtukhooypo.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gtclpwkfqr.html

python -m pytest -q
来源：http://dali.jqgfzy.top/Article/details/gtderuffif.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gtkgxauvst.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gtzoscwgdp.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gtamkveoet.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuetiantiany.cn/Article/details/gtvwkyeojb.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gtoagteyuw.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gtzvrzkdtb.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gtvtyzlqbq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwylxinf.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gtwkyewhbm.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gtfrifjdto.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gtjkbugxff.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gtcwbclwuo.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangdashe.top/Article/details/gtphdbyjbu.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gthfqismhz.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gtgzchcqku.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtnpwoeihn.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gtaotweaab.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfosxyxh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gtmohlgysh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenzaomai.com/Article/details/gtxwkikrjg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gtabuyiwkl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtukkzabvx.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gtewtwspkt.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gtqznrvtnp.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gttyvzsqqq.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gtdqkmnbsc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gtlaggppdw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtjewttahl.html

[U46] PHP：可空类型
来源：http://dali.xuanzx.com/Article/details/gtyynhyutw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gtpjmpwyvl.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gtdywvjfgs.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtgqhcgoqe.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gtmshozkwk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.haohaochexian.top/Article/details/gtpacrqlwx.html

[U49] PHP：只读属性
来源：http://dali.cashguo.top/Article/details/gtutgfwgvl.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gtjqbvnyau.html

[U50] PHP：构造器属性提升
来源：http://dali.sufxvd.cn/Article/details/gtlbjefcqr.html

public function __construct(private int $id) {}
来源：http://dali.haohaochexian.top/Article/details/gtiypfbbkh.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gtlianjwuw.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gtxxdjmwop.html

[U52] PHP：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtmzxuqhkg.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gteculzkvj.html


<!-- 参考信息 -->