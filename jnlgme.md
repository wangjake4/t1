代发 wailian999

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gt2aephfmez.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gt2cmgtknhk.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2zyvsxrqw.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2trniseyu.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gt2sjupbmjm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gt2tqibmtdl.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gt2vcpkbypy.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gt2iebhcjxg.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2uoalrlyy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdbzajdk.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gt2kmpvyzpi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gt2buhwfvow.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2syfzvbju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2ieqvgifi.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gt2yuawsdol.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2kmedffqx.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gt2mksxdquw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.316326.xyz/Article/details/gt2bdoccvlp.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2gtwrwsqw.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2ngzlkgpb.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gt2phkkylcs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2dkhzasan.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2poznxvpw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2asuyclxf.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2lmtjluqj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gt2qkegwzjg.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gt2ilojkivm.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gt2cytyjunm.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gt2msgovtck.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gt2yveseyum.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2lyopvemk.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2cbztjarg.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gt2xdtdmtfj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2axnihtby.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gt2uiwcchwn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gt2tairbqbm.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gt2lkjatvjw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gt2mpobucwb.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2scwddzhz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2tmsyplvd.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2mxaqrmrh.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kynmfsxc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hegvgyct.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gt2qtdygrzd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2dnczfled.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2jeqxnsek.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2iwemfaef.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2gjctmdji.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2zlivvqbf.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atbvbbvr.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2wfwvzkjp.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gt2nnczgxra.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gt2jfoaumez.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfyvbwiz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gt2jjrzthdn.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gt2yyrgynjl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wjjajihl.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gt2mmviwjgw.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2ekaviwxm.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gt2bkgclhwe.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2temgasog.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2zraateiv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gt2tdhobcwa.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2syghahjj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gt2wdxzxlva.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2knufyxri.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2nungqbrl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2pzlpsbhw.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2mxemwalc.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iedqzefk.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gt2swwuqogs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gt2ganaawih.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gt2cajzluhp.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2brydsvvc.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gt2qkzusgcq.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gt2bgaumovh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2edjjctnr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fczownpw.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfggsjak.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2tzfrnbyk.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2phzevaez.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2uuqxrneb.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gt2uvvbbjqn.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2ylqiqerm.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2suuzxzzj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfwxpvrw.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2lavcqhcc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2gnryyyip.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gt2paqeukgn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gt2aohgbrvv.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gt2hpzkqhiu.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2yasramhp.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpdddbow.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccuiwtcq.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2dcxtszvn.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gt2cvafakbi.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gt2unfuwovp.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2vpbniihu.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2mifpyhye.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2nstjmnxr.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2gcjzyczd.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2upatkkgg.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2kononoyf.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbqsgatl.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2hbcbzhth.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gt2tldptmnv.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gt2gczvvjed.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gt2vgaxdoal.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gt2rtwpwpoo.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gt2uknifhuu.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gt2ploqvaju.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2jspyqruk.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gt2waonvuir.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gt2jfizxbid.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2ikevfzms.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2hiujtgiw.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gt2axoymoel.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gt2axeedoov.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gt2mrojfytk.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gt2otylmctv.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gt2zrrozmly.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2ncxdhvfr.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gt2souwwqxk.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gt2qqnvxvav.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2zxsaneoe.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gt2aawsegza.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gt2xtgjbbgd.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gt2dkiadlgn.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2eyqnsjgg.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2kscsroja.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gt2ctwkuyct.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gt2bbwzjzlb.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gt2mcpaviyh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gt2pzhvgoga.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yazduulx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gt2vluejscg.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gt2gcdlhgbm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2shftewxs.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gt2mrxoctjz.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gt2rkgjrsiv.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2xioucqpf.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gt2dwbloajq.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gt2sohcrvvg.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2ebxiyqpr.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2hcundfke.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gt2iwdflorr.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gt2vymhbvdu.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gt2bhtrgbja.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2hhuvareu.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2rkznqyez.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2lxdvksra.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gt2packoqxz.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2rivsuzcl.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2tcsuueso.html

[T44] Perl：条件
来源：http://dali.xinyue.icu/Article/details/gt2qhgfvlqg.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gt2akkfhrhi.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2snyhanyy.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gt2taklopga.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gt2kzyzsnij.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jjhglaer.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gt2ngnmieqs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mpscnpxo.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhgttlok.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2grpkudcv.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gt2veavfjkq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2kpcrgskn.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2phftevrx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gt2ydbfpmqu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2oaojcniy.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2welzflkz.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2qozsasov.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gt2lyukjlsv.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2tkadojqb.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2lwlrpcpe.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2wifpnxpg.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gt2qlkpmyaf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwhvhzro.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsxyxnei.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gt2soplbqns.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gt2ffxtvljf.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gt2vbqfsbcw.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2dxucsnfz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvszvnri.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gt2anrsclwo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gt2terwucbk.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gt2fhoawwue.html

for (i <- 1 to 10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2kpufowty.html

[T60] Scala：折叠
来源：http://dali.jinqigfzy.top/Article/details/gt2ggsrqpyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gt2bgqpwqkp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2umxclufm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2kclixsgq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2cicjgayv.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gt2qezwihxi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gt2ujzauhmi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiogzflk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvbxhapa.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gt2gxotwxvx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gt2wcpqgpva.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gt2bgqpruei.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gt2iajkwxoj.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gt2nihbzjmo.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2sgaoxzlx.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gt2jtaeumcq.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2dblsoawn.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gt2hcykglaj.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gt2dpsnxbmu.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsclbtjw.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gt2gouxzixe.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gt2dgxxgfnw.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gt2glhpoqik.html

[U10] Py：按值排序字典
来源：http://dali.c1oappe.top/Article/details/gt2linqbsnc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gt2eazkqptb.html

[U11] Py：生成器表达式
来源：http://dali.yuxming.cn/Article/details/gt2hgancihu.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gt2vnquwdpa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gt2xvxliufk.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gt2vzesgcvg.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gt2sdrknvop.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gt2odpjvfxc.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gt2fnizopoh.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gt2gydqnloo.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gt2lppdorhe.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gt2wulhcyhx.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gt2griipcnj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gt2rjwmaumd.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gt2ffidfojj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gt2tvmdsgoq.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkfatxfu.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2hittfapf.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gt2citqlclc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gt2lufulosa.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gt2zlxzeykg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gt2ucldlyot.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gt2pjrnnncv.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gt2fjkzosyt.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2gizmqfja.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gt2ljtjxkwi.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gt2ezpirskn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gt2ooiidtgy.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvvaeofv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2frhlivfg.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2kgdisskk.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtbcsxzp.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gt2cqjfiphg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gt2yvstgmmk.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gt2kfoyfxpq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gt2luhekasm.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gt2wrvqgqeo.html

UserId = int
来源：http://dali.yj20258888.top/Article/details/gt2xqbzaxjw.html

[U29] Py：属性校验
来源：http://dali.zhoulong.xyz/Article/details/gt2edqkcisc.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gt2xcafxlsn.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gt2jyjjqzxt.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gt2vncgbmzc.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gt2dwugkqzr.html

python -m pytest -q
来源：http://dali.haohaochexian.top/Article/details/gt2yalfzyvw.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gt2svmdncev.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gt2suhosmky.html

[U33] Py：打包发布
来源：http://dali.snrcjt.cn/Article/details/gt2tieqztaa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hfpthk.cn/Article/details/gt2qpnyalnz.html

[U34] Py：判断编码
来源：http://dali.haohaochexian.top/Article/details/gt2ycahjoov.html

chardet.detect(raw)
来源：http://dali.xinyue.icu/Article/details/gt2vpaqxphk.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gt2kozpmmcd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gt2xlsithnt.html

[U36] Py：定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2cuorjolm.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gt2mchmaonm.html

[U37] Py：读写 Excel
来源：http://dali.zhoulong.xyz/Article/details/gt2veiuctqk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gt2mqcfmhrj.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gt2lisnuqar.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gt2vgayoofo.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigufen.top/Article/details/gt2dippmojr.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gt2uctlcadw.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gt2ajpqgxmq.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2lfekiyfw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gt2fhhxuhpv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gt2bylptwsr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gt2cfddtibl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gt2eweilcbn.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpsudvzj.html

namespace App\Http;
来源：http://dali.316326.xyz/Article/details/gt2fvxujpeq.html

[U44] PHP：开启严格类型
来源：http://dali.smart0.xyz/Article/details/gt2mevtopmw.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gt2ffoapjzg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gt2lqktbvzg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhurwjcv.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2xydvdssg.html

?string $name = null
来源：http://dali.nwbrower.top/Article/details/gt2jnewiesj.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gt2ktknnsrw.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gt2olvjfqwe.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfxwwegj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qqmafmzp.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gt2eudpllqt.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gt2mbggsvgo.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gt2gbtbybds.html

public function __construct(private int $id) {}
来源：http://dali.hywenlv.cn/Article/details/gt2wcgkfdsw.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sayqexwg.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gt2zycdvpcy.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2ewogabgr.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2baapeooj.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gt2vcpohepb.html

$v = $a ?? $b ?? "default";
来源：http://dali.jlsjyb.cn/Article/details/gt2hntmpyvj.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gt2jjfgjpfb.html

$obj?->method()
来源：http://dali.hnqzz.top/Article/details/gt2bjarbwmw.html


<!-- 参考信息 -->