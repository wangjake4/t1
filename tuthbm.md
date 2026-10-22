代发 wailian999

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lezekpkf.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2qnzxikyx.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gt2ythhclrg.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvpvmxka.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2epbvktue.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gt2hxylwltt.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2talhprjx.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2tunqvtsf.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2aetmzqxl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gt2gmlktjss.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gt2njfdocfi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gt2xybjmsdy.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2wezikwew.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2udchclrp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvmjuva.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzphnsyh.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gt2kmpflwfo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2uvzthzvb.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gt2zxbziivd.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2ylijwsqf.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gt2mjmoghxr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2bmpyggsu.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gt2rajeoskx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loejqcua.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2dfilrejs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gt2dxcvjkme.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkliegkq.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gt2nywsbkuw.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gt2vndteuco.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2wpggspbz.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chdrhzjz.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gt2tnyuflfh.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfhvfgqu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gt2msxytmge.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqktpyax.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gt2obssgmkf.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gt2oyhppaek.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2zlkuhfcm.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2zxypdzmo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gt2slypgyfz.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gt2fbsfjyva.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gt2mlujrvly.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gt2jjjfacfk.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evjsbzxr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2onvbfpeg.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2gwydcgsj.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gt2jenfpain.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2eaypmvle.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gt2gvfvwduf.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2cxselydy.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gt2skxtdkgj.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2nxylyxqm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqaotxn.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2nkaegvyn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gt2ozibonfu.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2qsupgwmw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gt2miybpjfh.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gt2wvxakbna.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gt2pnjieqhx.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2bdjlfgxm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2ryvfciff.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gt2hbwortpw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2qhebpwud.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gt2umbvmwkb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gt2bxzcaqhb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ptwyryhp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2seajtutg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdumsuop.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2smeqzfzo.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzqxghkt.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gt2vyijwqoa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2wrhpmdbc.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2vdciqvip.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2nkypglmr.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gt2ndmrtufq.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2buwoshqx.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2xxftesun.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gt2wbfocifh.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2ylgkrtaz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2wvetttky.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqnxfrvn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2bcoqfpai.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnaihuks.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znuwiwdj.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2fdozmevl.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gt2pvdokzxm.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gt2ixmcsvjp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdtaprqn.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gt2fztzgbdi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2mhtulhpq.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gt2lsyhcnmb.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2uyrpfnuw.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gt2onlttiul.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gt2cnbyftdp.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gt2isplmeru.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2djjigyml.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxfungfl.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gt2imzpbzpp.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2erahdjqy.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2yvytpxjp.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gt2rvjdjhym.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2wtmohkic.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2zozqbptb.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gt2nvsixgkm.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcwcbjsl.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gt2ojhnulhu.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gt2fcltfyog.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gt2eaudrfry.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gt2hfhvfmvj.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtlmdieo.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gt2klpbiszb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akqvzvel.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gt2nzkavmls.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2tnicirbu.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2ezfgcjcd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2nywnzfcp.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgrpuoby.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyasivmc.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2uwsiwpzi.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jldbwhcn.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gt2vuawcikr.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gt2licapqwt.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2eylwghwz.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gt2hsbsrqjw.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gt2euetjkeg.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gt2yyejlpwi.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gt2nasxselz.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gt2hfiymyoz.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2ualesprl.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2odfemtsc.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gt2oearlkog.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2inkwhuou.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gt2jazpvest.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gt2wcferzvf.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gt2trdpdhgq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itzgjzzn.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gt2oufnxepn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2gngmocqq.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2wnsbdlxf.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqlpoqan.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2gfvbcuyl.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gt2smyoynpt.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gt2tgrjqeep.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gt2upogzoxb.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2hrqwayka.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gt2vdigvnaw.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gt2mdbhzcde.html

setmetatable({}, { __index = base })
来源：http://dali.tianlin.xyz/Article/details/gt2ziwyojzp.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gt2hdakjhui.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gt2ytbrjxln.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2hbakzdve.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gt2bpqvupcd.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2jekefooa.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjjirnop.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywtemwby.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpjoivju.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gt2yvxaiqey.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gt2lhmfxvdm.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gt2edhkodwi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gt2ehkvatqs.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gt2jkspxrxt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gt2pfziprtr.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2kesnpsoq.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gt2lofovkpe.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gt2sqvzrezz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2tivwxboc.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2cemwqqcr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdjlukbk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gt2anqbptfa.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2quqvtehx.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2aowaaocl.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2ygdbdzjj.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2jpoiymry.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2zyickxos.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gt2vrnxtjrh.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2pjpkilpl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2mhnygcyu.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2ggikholf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gt2ljdzmxop.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gt2ucmelajf.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2vcyuppsf.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2jlbzezkr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gt2ywinywvi.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gt2mejrbdsi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aibaodan.cn/Article/details/gt2dkufskxr.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gt2nrieccds.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2ykthwqtu.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2tzxzbcji.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gt2yksxsxcs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ntveskqu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gt2ehlbalxc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2eubsdmqu.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gt2jxeapjmi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gt2vfapxznq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gt2anzfnodg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2icqbftoi.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gt2bntqtvnn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gt2wsrrapcr.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpfobdde.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gt2wdjalnfk.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2muhmqstx.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2hxrcipzn.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnlqwbgv.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gt2roolydqi.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gt2qcfmngpo.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gt2xfaptsus.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gt2zqjjoimy.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gt2qptiizqy.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gt2pwjhkmut.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gt2gifrudst.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gt2kszlhhrl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gt2nyeizxkt.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gt2evofukbq.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gt2rimxrczc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gt2ypxpugqf.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2fbzxycak.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gt2znxaqyvm.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gt2nfjculff.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gt2bncohuiz.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixudtxwb.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gt2csitvyqu.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqrnghry.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gt2gpmbujrp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gt2chfwzbjf.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gt2aayhedso.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gt2zfjugmvu.html

[U18] Py：预编译正则
来源：http://dali.yj20258.top/Article/details/gt2mrbwdvjd.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpyhcyux.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gt2rweyxcsb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gt2azmrkcep.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gt2qjshroal.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gt2xkxrqppn.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gt2xprikuft.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gt2lcervlfh.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gt2dzclshtt.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gt2huebtxjn.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gt2ohdwuzgh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtudvehp.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gt2xblvadny.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2gdlnelwg.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gt2bgdycbsx.html

csv.DictReader(f)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvzvhrir.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gt2adtvfkjv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gt2vkxsuqfq.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bubwvnvx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaolqqks.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gt2cyqjhlxx.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2vrhkujba.html

[U29] Py：属性校验
来源：http://dali.zycfv.cn/Article/details/gt2zjmjrbau.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gt2ulhfgkkd.html

[U30] Py：数据类
来源：http://dali.ybcxt.top/Article/details/gt2cqqazefl.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gt2npcgobhn.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gt2menyqngc.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gt2jfvchhah.html

[U32] Py：代码格式化
来源：http://dali.cheryme.top/Article/details/gt2bzhwsbow.html

ruff format . && ruff check --fix .
来源：http://dali.hnxiangtu.top/Article/details/gt2bnxclcsn.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gt2znwmieyq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwomfccj.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gt2imsxxvxb.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gt2vzocmwht.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gt2nqouhylv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.haohaochexian.top/Article/details/gt2tgrpuqrp.html

[U36] Py：定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2jmkrbuen.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhengqikj.top/Article/details/gt2mytoyzal.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gt2wbwnwswn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gt2txjjcuhq.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gt2hpwyhumv.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gt2zfujmbvq.html

[U39] Py：判断是否在交互环境
来源：http://dali.vqdsnc.cn/Article/details/gt2uwmkzujb.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsixvgip.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gt2blgnnzpi.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2ijrcmkjj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2aictzglp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gt2lrgkkpzo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuanzhike.top/Article/details/gt2pjqlwemx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gt2tbacvtvg.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gt2dkopfavm.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gt2wrwwhfad.html

[U44] PHP：开启严格类型
来源：http://dali.yongpay.top/Article/details/gt2dncsynmx.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gt2ohbfmwcq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhoulong.xyz/Article/details/gt2hkdkptia.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2xlvilvrr.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gt2szevjutv.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gt2bogcaefn.html

[U47] PHP：联合类型
来源：http://dali.nwbrower.top/Article/details/gt2fzmfcgsx.html

int|string $id
来源：http://dali.cucudq.cn/Article/details/gt2bsmmqqsd.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gt2gnezjnzp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gt2qdvctdrp.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gt2tzjinvvt.html

public readonly string $name
来源：http://dali.hnxiangtu.top/Article/details/gt2eufvzdga.html

[U50] PHP：构造器属性提升
来源：http://dali.svipenyu.cn/Article/details/gt2cceasxja.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrbijitu.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gt2bmavduxa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrdhiqk.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2xolxiqmu.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gt2jlenguef.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gt2wuzjnezm.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyomynfo.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gt2bpkordbp.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gt2wvuljfyr.html


<!-- 参考信息 -->